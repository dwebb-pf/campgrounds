# campgrounds
A personal project to showcase elixir skills

1. [Objectives](#objectives)
1. [Setup](#setup)
    1. [Install elixir](#install-elixir)
    1. [How to specify dependencies](#how-to-specify-dependencies)
    1. [How to install postgres](#how-to-install-postgres)
    1. [Repo Layout](#repo-layout)

## Objectives

1. Have code that can be used as a reference
1. Pull in data from a campground API
1. Store data in postgres
1. Fetch data from postgres
    * Search by location
        * city, state
        * lat, lon
    * Search text
        * fuzzy
        * vector search
1. Develop ui

## Setup

_[Back to Top](#campgrounds)_

### Install elixir
* Recommended to follow the instructions here:\
http://elixir-ko.github.io/install.html

_[Back to Top](#campgrounds)_

### Install dependencies

Dependencies are specified in the *deps/0* function in the *mix.exs* file located
> *add location*

_[Back to Top](#campgrounds)_

### How to install postgres

Install via guide located at:\
https://www.postgresql.org/download/

_[Back to Top](#campgrounds)_

### Repo Layout

_[Back to Top](#campgrounds)_

## Architecture

_[Back to Top](#campgrounds)_

* Docker
    * running application

* Postgres
    * Migrations
        * ecto
        * ecto_sql

* Phoenix framework

_[Back to Top](#campgrounds)_
