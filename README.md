# Open Decision

Open Decision is an Open-Source Decision Automation System, that is optimized for legal processes. The system will be used to build a platform to provide free legal advice for consumers.
Further information on open-decision.org

## Table of content
- [Getting Started](#getting-started)
- [Participate](#participate)
    - [Experts, Lawyers, Designers, Ambassadors, Enthusiasts & Unicorns](#for-experts-lawyers-designers-ambassadors-enthusiasts)
    - [Developers](#for-developers)
- [Set-Up](#set-up)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Built with](#built-with)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)


## Getting Started



## Participate


### For Experts, Lawyers, Designers, Ambassadors, Enthusiasts



### For Developers

We are happy about any contributions! Feel free to pick an issue, open a bug report, feature request or fork the project. We are open to any input or suggestions on how to bring the project forward. For further information feel free to join our [Slack-Channel](https://join.slack.com/t/opendecision/shared_invite/enQtNjM2NDUxNTQyNzU4LWYwMzJlZjlhOWJkMmIxMTBmMjYwMDE0Y2Y2OGUyZDBiY2FmOWU4OTVmMDFhMjNhNTIxYWZkZTNkNDRmNjQ4MmM)


##Set-up

The instructions down below will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to install Python and the package manager PIP. When you install Python <= 3.4 from the [official website](https://www.python.org/downloads/), PIP is already installed.

```
# Install virtual enviroment
pip install virtualenv
```

### Installation

First set-up and start the virtual environment.

```
# Create virtualenv
virtualenv -p python3 od

# Start environment
source od/bin/activate

```

Now clone the repo to the "src"-folder or download the [repo](https://github.com/fbennets/open-decision) as zip, unpack the folder, move it into the folder of your environment and rename it to "src".

```
# Clone repository to current directory
cd od
git clone https://github.com/fbennets/open-decision.git src

```
Next install the requirements.

```
# Install dependencies
cd src
pip install -r requirements.txt
```
Now start the Django development server and enjoy!

```
# Start the development server
python manage.py runserver
```

Now you can create an account and start playing around with Open Decision!


## Built With

* [Django](https://www.djangoproject.com/) - The web framework used


## Contributing

Please read [CONTRIBUTING.md]() for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Links

* [Project Website](http://open-decision.org)
* [Join our Slack-Channel](https://join.slack.com/t/opendecision/shared_invite/enQtNjM2NDUxNTQyNzU4LWYwMzJlZjlhOWJkMmIxMTBmMjYwMDE0Y2Y2OGUyZDBiY2FmOWU4OTVmMDFhMjNhNTIxYWZkZTNkNDRmNjQ4MmM)
* [Documentation](https://open-decision.readthedocs.io/en/latest/)
