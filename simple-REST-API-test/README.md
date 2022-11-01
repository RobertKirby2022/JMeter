<h1>Overview</h1>
A Simple REST API test performed with JMeter.
<h2>Test Plan</h2>

![TestPlan](https://user-images.githubusercontent.com/107216125/199130803-273a6ef4-1874-4333-a817-6672704af26f.png)
This test was created to test a weather web service API.
<h2>Thread Group</h2>

![ThreadGroup](https://user-images.githubusercontent.com/107216125/199130890-37da1853-a8bc-496d-9296-e548a9b3adcf.png)
Two users or threads were created for this test.
<h2>Sampler</h2>

![Sampler](https://user-images.githubusercontent.com/107216125/199130955-92fee841-63e5-4db8-b9e0-7d8f579a59d4.png)
The HTTP GET request has two parameters: The city we wish to gather weather data for and our API key.
<h2>Listener</h2>

![Listener-Results](https://user-images.githubusercontent.com/107216125/199131110-0087b488-2240-4d7e-96e2-1f3135756719.png)
A listener is setup to capture results. The green arrow shows relevant data related to performance. The red arrow shows the response.
<h2>Results</h2>

![Results](https://user-images.githubusercontent.com/107216125/199131241-4092f46f-3428-496e-baa1-84a21c5677e2.png)
The Response Data tab shows our actual data received from our request. It appears London is in for some rain!

NOTES: JMeter appears to be a powerful testing tool. Its simple GUI allows for easy and fast testing of REST API web services.
