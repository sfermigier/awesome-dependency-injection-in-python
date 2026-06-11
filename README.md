# Awesome Dependency Injection in Python

> A curated list of awesome things related to dependency inversion / dependency injection in Python.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


## Talks / slides

- **Python Dependency Injection** [(PDF)](http://www.aleax.it/yt_pydi.pdf) (Alex Martelli, 2008).
- Fang: Pythonic dependency injection [(video)](https://www.youtube.com/watch?v=zqRd941NXlI&t=443s) (Nathan Craike, 2015).

## Videos

- [Loose Coupling & Dependency Injection the EASY Way!](https://www.youtube.com/watch?v=uWTvMCra-_Y) (Hynek Schlawack, 2024)
- [Dependency Inversion: Write BETTER PYTHON CODE Part 2](https://www.youtube.com/watch?v=Kv5jhbSkqLE) (ArjanCodes, 2021)
- [Dependency INVERSION vs Dependency INJECTION in Python](https://www.youtube.com/watch?v=2ejbLVkCndI) (ArjanCodes, 2021)


## Articles / blog posts

- [Enforcing Single Responsibility Principle in Python](https://sobolevn.me/2019/03/enforcing-srp) (Nikita Sobolev / Никита Соболев, 2019)
- [Pythonic Dependency Injection: A Practical Guide](https://medium.com/@suneandreasdybrodebel/pythonic-dependency-injection-a-practical-guide-83a1b1299280) (Sune Andreas Dybro Debel, 2018)
- [Elegant Flask API Development Part 1](https://christophergs.github.io/python/2018/09/25/elegant-flask-apis-pt-1/) (mostly covers Flask-Injector).
- ["(pytest) Fixtures: a prime example of dependency injection"](https://docs.pytest.org/en/latest/fixture.html#fixtures-a-prime-example-of-dependency-injection)
- [Tests and comparison of Python dependency injection libraries](https://github.com/orsinium/dependency_injectors) ★3 - Tests and comparison of Python dependency injection libraries. [🐍, Unknown license].
- [Typed Functional Dependency Injection in Python](https://sobolevn.me/2020/02/typed-functional-dependency-injection)
- [DI patterns](https://lab.abilian.com/Tech/Architecture%20%26%20Design/Dependency%20Inversion/DI%20patterns/) (Abilian, 2024)
- [DI anti-patterns](https://lab.abilian.com/Tech/Architecture%20%26%20Design/Dependency%20Inversion/DI%20anti-patterns/) (Abilian, 2024)


## Books

- [Pythonic Application Architecture Patterns for Managing Complexity](https://github.com/python-leap/book) ★3737 - A Book about Pythonic Application Architecture Patterns for Managing Complexity.  Cosmos is the Opposite of Chaos you see. O'R. wouldn't actually let us call it "Cosmic Python" tho. [🐍, Other license].


## Software

### DI Frameworks / Containers

- [python-dependency-injector](https://github.com/ets-labs/python-dependency-injector) ★4833 - Dependency injection framework for Python. [🐍, BSD 3-Clause "New" or "Revised" License].
- [returns](https://github.com/dry-python/returns) ★4244 - Make your functions return something meaningful, typed, and safe!. [🐍, BSD 2-Clause "Simplified" License].
- [Injector](https://github.com/alecthomas/injector) ★1513 - Python dependency injection framework, inspired by Guice. [🐍, BSD 3-Clause "New" or "Revised" License].
- [Dishka](https://github.com/reagento/dishka) ★1109 - Cute DI framework with agreeable API and everything you need. [🐍, Apache License 2.0].
- [Inject](https://github.com/ivankorobkov/python-inject) ★770 - Python dependency injection. [🐍, Apache License 2.0].
- [FastDepends](https://github.com/lancetnik/FastDepends) ★497 - FastAPI Dependency Injection system extracted from FastAPI and cleared of all HTTP logic. [🐍, MIT License].
- [Kink](https://github.com/kodemore/kink) ★438 - Dependency injection container made for Python. [🐍, MIT License].
- [Punq](https://github.com/bobthemighty/punq) ★418 - An IoC container for Python 3.6+. [🐍, MIT License].
- [svcs](https://github.com/hynek/svcs) ★403 - A Flexible Service Locator for Python. [🐍, MIT License].
- [Wireup](https://github.com/maldoinc/wireup) ★373 - Concise, Powerful, and Type-Safe Python Dependency Injection Library. [🐍, MIT License].
- [di](https://github.com/adriangb/di) ★335 - Pythonic dependency injection. [🐍, MIT License].
- [Lagom](https://lagom-di.readthedocs.io/en/latest/) ★246: Type based auto-wiring dependency injection with support for async and threading. [🐍, MIT License].
- [That Depends](https://github.com/modern-python/that-depends) ★244 - simple DI-framework, inspired by python-dependency-injector, but without wiring [🐍, MIT License].
- [Rodi](https://github.com/RobertoPrevato/rodi) ★234 - Implementation of dependency injection for Python 3. [🐍, MIT License].
- [diwire](https://github.com/maksimzayats/diwire) ★217 - Type-safe dependency injection for Python with auto-wiring, scopes, async factories, and zero deps [🐍, MIT License].
- [python-injection](https://github.com/100nm/python-injection) ★126 - Dead-simple dependency injection framework for Python. [🐍, MIT License].
- [injectable](https://github.com/allrod5/injectable) ★118 - Python Dependency Injection for Humans™. [🐍, MIT License].
- [Opyoid](https://github.com/illuin-tech/opyoid) ★76 - Dependency injection library for Python. [🐍, MIT License].
- [Modern DI](https://github.com/modern-python/modern-di) ★50 - powerful DI-framework with scopes and IoC-container [🐍, MIT License].
- [Picodi](https://github.com/yakimka/picodi) ★31 - A DI library inspired by FastAPI. It integrates well with FastAPI but can also be used independently. [🐍, MIT License].
- [andi](https://github.com/scrapinghub/andi) ★24 - Library for annotation-based dependency injection. [🐍, BSD 3-Clause "New" or "Revised" License].
- [Fresh Bakery](https://github.com/Mityuha/fresh-bakery) ★21 - Bake dependency injections asynchronously and stupidly simple. [🐍, MIT License].
- [engin](https://github.com/invokermain/engin) ★20 - a dependency injection powered application framework, inspired by [Uber's fx framework](https://github.com/uber-go/fx). [🐍, MIT License].
- [ididi](https://github.com/raceychan/ididi) ★19  - Genius simplicity, unmathced power, dependency injection in a single line of code. [🐍, MIT License]
- [injection](https://github.com/nightblure/injection) ★18 - replacement for [python-dependency-injector](https://github.com/ets-labs/python-dependency-injector) that works with Python 3.8-3.12 and works with FastAPI, DRF, Flask and Litestar [🐍, MIT License].
- [Clean IoC](https://github.com/peter-daly/clean_ioc) ★10 - A simple unintrusive dependency injection library for python with strong support for generics [🐍, MIT License].
- [Overlay](https://github.com/Atry/MIXINv2) ★6 - A dependency injection framework with pytest-fixture syntax, plus a configuration language for declarative programming [🐍, MIT License].
- [Injex](https://github.com/vshulcz/injex) ★6 - Tiny typed dependency injection container with constructor injection, singleton/transient/scoped lifetimes, test overrides, and graph validation before startup. Zero runtime dependencies. [🐍, MIT License].

### DI components of Web frameworks

Several modern Python web frameworks include DI components, including:

- FastAPI -> [Dependencies - First Steps](https://fastapi.tiangolo.com/tutorial/dependencies/).
- Litestar -> [Dependency Injection](https://docs.litestar.dev/2/usage/dependency-injection.html).
- Sanic -> [Dependency Injection](https://sanic.dev/en/plugins/sanic-ext/injection.html).
- Xpresso -> [di](https://github.com/adriangb/di) (see above)
- Blacksheep -> [Rodi](https://github.com/RobertoPrevato/rodi) (see above)


### Integration with web frameworks

- [Flask-Injector](https://github.com/alecthomas/flask_injector) ★283 - Adds Injector support to Flask. [🐍, BSD 3-Clause "New" or "Revised" License].

See also above.
