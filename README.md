# Ruby on Rails Simple Twitter Clone

This is the sample application for
[*Ruby on Rails Tutorial: Learn Web Development with Rails*](http://www.railstutoial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).

## License

All source code in the [Ruby on Rails Tutorial](http://railstutorial.org/)
is available jointly under MIT Licence and the Beerware License. See [LICENSE.md](LICENSE.md) for details.

## Getting started 

to get started with the app clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:
```
$ rails db:migrate
```

Finally, run the test suite to verify that evertying is working correctly:
```
$ rails test
```

If the test suite passes, you'll be ready to run the app in the local server:
```
$ rails server
```

For more information, see the [*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book)