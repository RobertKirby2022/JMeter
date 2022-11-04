<h1>Overview</h1>
A Simple REST API test performed with JMeter.
<h2>Test Plan</h2>

![TestPlan](https://user-images.githubusercontent.com/107216125/200086032-a8837ea3-8434-4d76-bb7c-9fc76229a80f.png)
This test was created to test a weather web service API.
<h2>Thread Group</h2>

![ThreadGroup](https://user-images.githubusercontent.com/107216125/200086045-3fa9d4a5-a25a-47b5-a0b0-a457ef268539.png)
Two users or threads were created for this test.
<h2>Sampler</h2>

![InkedSampler](https://user-images.githubusercontent.com/107216125/200086056-9c93d107-90fb-40aa-bd16-95fbf7bb9378.jpg)
The HTTP GET request has two parameters: The city we wish to gather weather data for and our API key.
<h2>Listener</h2>

![Listener](https://user-images.githubusercontent.com/107216125/200086076-018b0863-8dd9-4006-aa0b-fd9b5c933a5e.png)
A listener is setup to capture results. The green arrow shows relevant data related to performance. The red arrow shows the response.
<h2>Results</h2>

![Results](https://user-images.githubusercontent.com/107216125/200086091-26265b5a-3ee1-4ec2-acc1-ec5f777b4ee4.png)
The Response Data tab shows our actual data received from our request. It appears London is in for some rain!

NOTES: JMeter appears to be a powerful testing tool. Its simple GUI allows for easy and fast testing of REST API web services.
