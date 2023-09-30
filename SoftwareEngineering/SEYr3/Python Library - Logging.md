Logging is a means of tracking events that happen when some software runs. While it can be used for error reporting, it is also a valuable tool for diagnosing, understanding the flow, and even debugging code.

[[Python]] provides a built-in logging module as part of its standard library, offering a flexible framework for emitting log messages from [[Python]] programs. This module is widely used and provides a way to configure different log levels, handlers, and formatters

DEBUG $\to$ INFO $\to$ WARNING $\to$ ERROR $\to$ CRITICAL

- DEBUG: Detailed information, typically only of interest when diagnosing problems
- INFO: Confirmation that things are working as expected
- WARNING: An indication that something unexpected happened or there may be a problem in the near future (e.g. disk space low). The software is still working as expected however
- ERROR: Due to a more serious problem, the software has not been able to perform some function
- CRITICAL: A very serious error, indicating that the program itself may be unable to continue running

```python
import logging

logging.basicConfig(level=logging.WARNING, format='%(asctime)s - %(filename)s[line:%(lineno)d] - %(levelname)s: %(message)s')

# using logging feature, by default the logging level is warning
logging.debug('This is loggging debug message')
logging.info('This is loggging info message')
logging.warning('This is loggging a warning message')
logging.error('This is an loggging error message')
logging.critical('This is loggging critical message')

#>WARNING:root:This is loggging a warning message
#>ERROR:root:This is an loggging error message
#>CRITICAL:root:This is loggging critical message

logger = logging.getLogger('my_logger')
  
logging.basicConfig(level=logging.DEBUG)

logging.debug('This WILL get logged')
#>DEBUG:root:This WILL get logged
```