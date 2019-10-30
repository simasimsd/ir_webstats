# iRWebStats

You can use iRWebStats to send requests to iRacing service and get some valuable data like stats, race results, driver info, series info, etc. it requires valid login credentials (username and password) to access the service.

## Getting Started
### Prerequisites

Python 3+ (with network access)

### Installing

Install using pip and git url

```
pip install git+https://github.com/simasimsd/ir_webstats.git#egg=ir_webstats
```

### Usage
```
irw = iRWebStats()
irw.login('username', 'password')
print (irw.cars_driven())  # cars driven by user
```
