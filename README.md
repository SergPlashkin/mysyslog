# mysyslog: A Modular Logging System

This project is a educational implementation of a flexible logging system in C. It consists of a core library, format plugins (drivers), a client utility, and a logging daemon.

## Repository Structure
*   `libmysyslog/` - Core logging library with plugin support.
*   `libmysyslog-text/` - Plugin for plain text log format.
*   `libmysyslog-json/` - Plugin for JSON log format.
*   `mysyslog-client/` - Command-line tool to send log messages.
*   `mysyslog-daemon/` - Daemon for automatic, repeated logging.
