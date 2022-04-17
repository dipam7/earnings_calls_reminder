# earnings_calls_reminder

I love listening to earnings calls, they're a great way to keep up with a company and check management's vision for the future. It would be nice to get a notification on my Mac or automated reminders in my calendar about these earnings calls. This repo tries to build on top of yahoo-earnings-calendar to do just that.

Company tickers go in `companies.txt`, one ticker on one line. Example

```
FB
DOCU
ROKU
TTD
```

We check for the next earnings date for all these tickers, and if it falls in the upcoming week, then we add reminder (in the form of notification, email, text, calendar, etc)

## Installation

Poetry installation [instructions](https://python-poetry.org/docs/)

Installing python requirements
```
poetry install
```

updating requirements
```
poetry update
```

Activating shell
```
poetry shell
```

## Based on

[yahoo-earnings-calendar](https://github.com/wenboyu2/yahoo-earnings-calendar)
