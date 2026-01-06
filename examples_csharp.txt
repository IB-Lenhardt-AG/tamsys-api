// LOGIN - Get Bearer Token
var client = new HttpClient();
var request = new HttpRequestMessage(HttpMethod.Post, "https://tamsys.org/webapi/v1/api.php/login/auth");
var content = new StringContent("{\n    \"credentials\": {\n        \"token\": \"{YOUR_ACCESS_TOKEN}\",\n        \"key\": \"{YOUR_SECRET_KEY}\"\n    }\n}", null, "application/json");
request.Content = content;
var response = await client.SendAsync(request);
response.EnsureSuccessStatusCode();
Console.WriteLine(await response.Content.ReadAsStringAsync());

// TEST - Check if logged in correctly
var client = new HttpClient();
var request = new HttpRequestMessage(HttpMethod.Post, "https://tamsys.org/webapi/v1/api.php/Login/test");
request.Headers.Add("Authorization", "Bearer {YOUR_BEARER_TOKEN}}");
var content = new StringContent("{\n    \"credentials\": {\n        \"token\": \"{YOUR_ACCESS_TOKEN}\",\n        \"key\": \"{YOUR_SECRET_KEY}\"\n    }\n}", null, "application/json");
request.Content = content;
var response = await client.SendAsync(request);
response.EnsureSuccessStatusCode();
Console.WriteLine(await response.Content.ReadAsStringAsync());
