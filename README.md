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
- [Tests and comparison of Python dependency injection libraries](https://github.com/orsinium/dependency_injectors) ★3
- [Typed Functional Dependency Injection in Python](https://sobolevn.me/2020/02/typed-functional-dependency-injection)


## Books

- [Pythonic Application Architecture Patterns for Managing Complexity](https://github.com/python-leap/book) ★2959, see specially this chapter: [Dependency Injection (And Mocks)](https://github.com/python-leap/book/blob/master/chapter_12_dependency_injection.asciidoc)


## Software

### DI Frameworks

- [returns](https://github.com/dry-python/returns) ★2740: "Make your functions return something meaningful, typed, and safe!". Part of the [dry-python](https://github.com/dry-python) ecosystem.
- [python-dependency-injector](https://github.com/ets-labs/python-dependency-injector) ★2894: "Dependency injection microframework for Python"
- [Injector](https://github.com/alecthomas/injector) ★947: "Python dependency injection framework, inspired by Guice".
- [Inject](https://github.com/ivankorobkov/python-inject) ★556: Python dependency injection
- [Dependencies](https://github.com/proofit404/dependencies) ★335: "Constructor injection designed with OOP in mind."
- [Punq](https://github.com/bobthemighty/punq) ★227: "An IoC container for Python 3.6+."
- [di](https://github.com/adriangb/di) ★189: Pythonic dependency injection. Used by (and developped for) the [Xpresso](https://xpresso-api.dev/) Web framework.
- [injectable](https://github.com/allrod5/injectable) ★94: "Injectable: Dependency Injection for Humans™"
- [Antidote](https://github.com/Finistere/antidote) ★84: "Dependency injection for Python"
- [Rodi](https://github.com/RobertoPrevato/rodi) ★80: Dependency injection for Python 3 (used by, and developped for, the [BlackSheep](https://github.com/Neoteroi/BlackSheep) web framework).
- [Lagom](https://lagom-di.readthedocs.io/en/latest/) ★30: Type based auto-wiring dependency injection with support for async and threading.
- [Bevy](https://github.com/ZechCodes/Bevy) ★22: "Bevy makes using Dependency Injection in Python a breeze so that you can focus on creating amazing code."
- [Kink](https://github.com/kodemore/kink) ★211: "Dependency injection container made for Python"


### DI components of Web frameworks

Several modern Python web frameworks include DI components, including:

- FastAPI -> [Dependencies - First Steps](https://fastapi.tiangolo.com/tutorial/dependencies/).
- Litestar -> [Dependency Injection](https://docs.litestar.dev/2/usage/dependency-injection.html).
- Sanic -> [https://sanic.dev/en/plugins/sanic-ext/injection.html](https://sanic.dev/en/plugins/sanic-ext/injection.html).
- Xpresso -> [di](https://github.com/adriangb/di) (see above)
- Blacksheep -> [Rodi](https://github.com/RobertoPrevato/rodi) (see above)
- Aiodine (dead, see below) was the DI framework for the Bocadillo project (also dead)


#### Archived or unmaintained DI frameworks

- [Serum](https://github.com/suned/serum) ★84: "Dependency injection framework for Python 3.6" (unmaintained)
- [Aiodine](https://github.com/bocadilloproject/aiodine) ★54: "Async-first Python dependency injection library" (unmaintained)
- [Wiring](https://github.com/msiedlarek/wiring) ★27: Architectural foundation for Python applications. (Unmaintained).


### Integration with web frameworks

- [Flask-Injector](https://github.com/alecthomas/flask_injector) ★246: Adds Injector support to Flask.
- [Pyramid-Wiring](https://github.com/veeti/pyramid_wiring) ★0: integration of Wiring and Pyramid (unmaintained).

See also above.
