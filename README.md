<br />
<p align="center">
  <h3 align="center">Youtube API System</h3>
</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [About the Project](#about-the-project)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)

<!-- ABOUT THE PROJECT -->

## About The Project

**To make an API to fetch latest videos sorted in reverse chronological order of their publishing date-time from YouTube for a given tag/search query in a paginated response.
Implemented this project using Django with the latest Async views.
Created an app \***api**_ inside the django project.Under the views of the _**api**_ enabled
the latest django async features.
Also created a model for the _**videos**_ with a _**GET API\*\*\* which returns
the stored video data sorted in descending order of published datetime.

### Built With

- [Django](https://www.djangoproject.com/)
- [Python](https://www.python.org/)

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple steps.

### Installation

1. Clone the repo

```sh
git clone https://github.com/Saurabhsahab/Fampay-Assgnmt-Solution.git
```

2. Install Django

```sh
pip install django
```

<!-- USAGE EXAMPLES -->

## Usage

To run this project locally, you can run the following command.

#### Using npm

```sh
python manage.py runserver
```

## API Endpoints

| Request Type | Route  | Function |
| :----------: | :----: | :------: |
|     Get      |   /    |   Home   |
|     Get      | /video |  Videos  |

**UI**
![Screenshot (163)](https://user-images.githubusercontent.com/63347618/177000939-16bddd5e-c375-4594-a308-9ceba2301abe.png)

![Screenshot (161)](https://user-images.githubusercontent.com/63347618/177000909-32504461-3d98-4a05-afd5-6ba980f7fb3e.png)

![Screenshot (162)](https://user-images.githubusercontent.com/63347618/177000944-82f656a6-b5c5-466b-8a0d-487685e7165a.png)
