<h1 align="center">
  <br>
  Yad2CarSearch
  <br>
</h1>

<h4 align="center">A minimal app built on top of python and selenium.</h4>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a>
</p>

## Key Features

* Made a template for any price tracking site to mimic human behaviour
  - Bypassing sites protection against automated scripts to mine them such as [Amazon](https://www.amazon.com/)
* Filter By car maker and module - See list of currently supported moduls in yad2_config
* Filters out cars without a price and different basic features
* Cross platform
  - Windows, macOS and Linux ready.

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Python3](https://www.python.org/download/releases/3.0/) (and using this guide to install [pip & venv](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/itsmeboris/yad2-car-search

# Go into the repository
$ cd yad2-car-search

# Create a venv and run it
$ python3 -m venv env
$ source env/bin/activate

# Install requirements from requirements.txt
$ pip install -r requirements.txt

# Run the app
$ python3 .\simple_tracker.py
```

## Output

The output will be in a JSON file called output.json and will have a list of cars, sorted by their maker. See output.json for an example.

## Credits

This software uses the following open source packages:

- [Python3](https://www.python.org/download/releases/3.0/)
- [pip](https://pypi.org/project/pip/)
- [selenium](https://www.selenium.dev/)

## License

MIT

---
