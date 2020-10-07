+++
title = "Logging"

[extra]

intro = "Logging is part of the rust ecosystem for a long time and with log and env_logger you have some great defaults."

level = 1

packages = [
  "log",
  "env_logger",
  "fern",
  "log4rs",
  "logger",
  "syslog",
  "flexi_logger",
  "json_logger",
  "sentry",
  "slog"
]

newstag = "logging"
+++

{{ packages(packages='packages') }}