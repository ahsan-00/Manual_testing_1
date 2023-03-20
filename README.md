
# Manual Testing for "Unimassbd"


The purpose of this test plan is to ensure that Unimassbd Real Estate website meets the quality standards and customer expectations. This test plan outlines the test objectives, test strategies, and test approach to be used to achieve the desired outcomes.


## Prerequisites
Understanding of the Unimassbd. Beacause, here I'm gonna testing, including its features, functionality, and business requirements.

 - Test environment:Browsers, Operating Systems, Devices, 
 - Test data: Verious type of data.
 - Test plan: Solid Test plan.
 - Test scripts: N/A here
 - Testing tools:JMeter
## Installing
The following software and tools need to be install for the test:

- Browser: Different browsers such as Google Chrome, Mozilla Firefox
- Operating system: Windows/linux
- Screen recording software: AwesomeScreenshot.
- Bug tracking tool: JIRA.
## API Reference

#### Get all items

```http
  https://unimassbd.com/
  https://unimassbd.com/about
  https://unimassbd.com/projects
  https://unimassbd.com/query
  https://unimassbd.com/event
  https://unimassbd.com/contact
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. nUll0 |

#### Get item

```http
  GET /https://unimassbd.com/items/${10}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `10`      | `string` | **Required**. 10 of item to fetch |



## Running Tests

![App Screenshot](https://github.com/ahsan-00/Manual_testing_1/blob/master/Capture.PNG?raw=true)


![App Screenshot](https://github.com/ahsan-00/Manual_testing_1/blob/master/xxx.PNG?raw=true)

## Environment Variables

As I mentioned earlier, for manual testing, there may not be specific environment variables that are required to be set up as the testing is performed manually by a human tester. Therefore, the concept of environment variables may not be directly applicable to manual testing.

 - Test environment:Browsers, Operating Systems, Devices, 
 - Test data: Verious type of data.
 - Test plan: Solid Test plan.
 - Test scripts: N/A here
 - Testing tools:JMeter
 
## Badges
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)



## Authors
 Thanks for 
- [@Ahsan](https://github.com/ahsan-00)


## Acknowledgments

I would like to thank the following individuals and organizations for their contributions to this project:
This project is released under the MIT License.


