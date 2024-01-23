# Awesome Dependency Injection in Python

> A curated list of awesome things related to dependency inversion / dependency injection in Python.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


## Talks / slides

- **Python Dependency Injection** [(PDF)](http://www.aleax.it/yt_pydi.pdf) (Alex Martelli, 2008).
- Fang: Pythonic dependency injection [(video)](https://www.youtube.com/watch?v=zqRd941NXlI&t=443s) (Nathan Craike, 2015).


## Articles / blog posts

- [Enforcing Single Responsibility Principle in Python](https://sobolevn.me/2019/03/enforcing-srp) (Nikita Sobolev / Никита Соболев, 2019)
- [Pythonic Dependency Injection: A Practical Guide](https://medium.com/@suneandreasdybrodebel/pythonic-dependency-injection-a-practical-guide-83a1b1299280) (Sune Andreas Dybro Debel, 2018)
- [Elegant Flask API Development Part 1](https://christophergs.github.io/python/2018/09/25/elegant-flask-apis-pt-1/) (mostly covers Flask-Injector).
- ["(pytest) Fixtures: a prime example of dependency injection"](https://docs.pytest.org/en/latest/fixture.html#fixtures-a-prime-example-of-dependency-injection)
- [Tests and comparison of Python dependency injection libraries](https://github.com/orsinium/dependency_injectors) ★3 - Tests and comparison of Python dependency injection libraries. [🐍, Unknown license].
- [Typed Functional Dependency Injection in Python](https://sobolevn.me/2020/02/typed-functional-dependency-injection)
- [DI patterns](https://lab.abilian.com/Tech/Architecture/Dependency%20Inversion/DI%20patterns/) (Abilian, 2024)
- [DI anti-patterns](https://lab.abilian.com/Tech/Architecture/Dependency%20Inversion/DI%20anti-patterns/) (Abilian, 2024)


## Books

- [Pythonic Application Architecture Patterns for Managing Complexity](https://github.com/python-leap/book) ★3167 - A Book about Pythonic Application Architecture Patterns for Managing Complexity.  Cosmos is the Opposite of Chaos you see. O'R. wouldn't actually let us call it "Cosmic Python" tho. [🐍, Other license].


## Software

### DI Frameworks / Containers

- [python-dependency-injector](https://github.com/ets-labs/python-dependency-injector) ★3429 - Dependency injection framework for Python. [🐍, BSD 3-Clause "New" or "Revised" License].
- [returns](https://github.com/dry-python/returns) ★3082 - Make your functions return something meaningful, typed, and safe!. [🐍, BSD 2-Clause "Simplified" License].
- [Injector](https://github.com/alecthomas/injector) ★1102 - Python dependency injection framework, inspired by Guice. [🐍, BSD 3-Clause "New" or "Revised" License].
- [Inject](https://github.com/ivankorobkov/python-inject) ★611 - Python dependency injection. [🐍, Apache License 2.0].
- [Dependencies](https://github.com/proofit404/dependencies) ★353 - Constructor injection designed with OOP in mind. [🐍, BSD 2-Clause "Simplified" License].
- [Kink](https://github.com/kodemore/kink) ★285 - Dependency injection container made for Python. [🐍, MIT License].
- [Punq](https://github.com/bobthemighty/punq) ★258 - An IoC container for Python 3.6+. [🐍, MIT License].
- [di](https://github.com/adriangb/di) ★255 - Pythonic dependency injection. [🐍, MIT License].
- [svcs](https://github.com/hynek/svcs) ★169 - A Flexible Service Locator for Python. [🐍, MIT License].
- [Rodi](https://github.com/RobertoPrevato/rodi) ★125 - Implementation of dependency injection for Python 3. [🐍, MIT License].
- [injectable](https://github.com/allrod5/injectable) ★101 - Python Dependency Injection for Humans™. [🐍, MIT License].
- [Antidote](https://github.com/Finistere/antidote) ★89 - Dependency injection for Python. [🐍, MIT License].
- [Bevy](https://github.com/ZechCodes/Bevy) ★68 - A dependency injection framework for Python! Bevy's primary goal is to help you write amazing code with less effort. [🐍, MIT License].
- [Opyoid](https://github.com/illuin-tech/opyoid) ★56 - Dependency injection library for Python. [🐍, MIT License].
- [Wireup](https://github.com/maldoinc/wireup) ★40 - Concise, Powerful, and Type-Safe Python Dependency Injection Library. [🐍, MIT License].
- [Lagom](https://lagom-di.readthedocs.io/en/latest/) ★30: Type based auto-wiring dependency injection with support for async and threading.
- [Fresh Bakery](https://github.com/Mityuha/fresh-bakery) ★17 - Bake dependency injections asynchronously and stupidly simple. [🐍, MIT License].
- [andi](https://github.com/scrapinghub/andi) ★17 - Library for annotation-based dependency injection. [🐍, BSD 3-Clause "New" or "Revised" License].


### DI components of Web frameworks

Several modern Python web frameworks include DI components, including:

- FastAPI -> [Dependencies - First Steps](https://fastapi.tiangolo.com/tutorial/dependencies/).
- Litestar -> [Dependency Injection](https://docs.litestar.dev/2/usage/dependency-injection.html).
- Sanic -> [Dependency Injection](https://sanic.dev/en/plugins/sanic-ext/injection.html).
- Xpresso -> [di](https://github.com/adriangb/di) (see above)
- Blacksheep -> [Rodi](https://github.com/RobertoPrevato/rodi) (see above)
- Aiodine (dead, see below) was the DI framework for the Bocadillo project (also dead)


### Archived or unmaintained DI frameworks

- [Serum](https://github.com/suned/serum) ★84 - Dependency injection framework for Python 3.6. [🐍, MIT License].
- [Aiodine](https://github.com/bocadilloproject/aiodine) ★53 - 🧪 Async-first Python dependency injection library. [🐍, MIT License].
- [Wiring](https://github.com/msiedlarek/wiring) ★27 - Architectural foundation for Python applications. [🐍, Apache License 2.0].


### Integration with web frameworks

- [Flask-Injector](https://github.com/alecthomas/flask_injector) ★263 - Adds Injector support to Flask. [🐍, BSD 3-Clause "New" or "Revised" License].
- [svcs](https://github.com/hynek/svcs) ★169 - A Flexible Service Locator for Python. [🐍, MIT License].
- [Wireup](https://github.com/maldoinc/wireup) ★40 - Concise, Powerful, and Type-Safe Python Dependency Injection Library. [🐍, MIT License].

See also above.
