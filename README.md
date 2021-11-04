# :zap: Angular Ngrx Energy

* Angular app to show API data on energy in the Danish energy markets.
* Tutorial code from [Lars Gyrup Brink Nielsen of Angular After Dark](https://www.youtube.com/channel/UCsZWzmsdKz2VA49XXBK5TQA)
* **Note:** to open web links in a new window use: _ctrl+click on link_

![GitHub repo size](https://img.shields.io/github/repo-size/AndrewJBateman/angular-ngrx-energy?style=plastic)
![GitHub pull requests](https://img.shields.io/github/issues-pr/AndrewJBateman/angular-ngrx-energy?style=plastic)
![GitHub Repo stars](https://img.shields.io/github/stars/AndrewJBateman/angular-ngrx-energy?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/AndrewJBateman/angular-ngrx-energy?style=plastic)

## :page_facing_up: Table of contents

* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## :books: General info

* f

## :camera: Screenshots

![Frontend screenshot](./img/home.png)

## :signal_strength: Technologies

* [Nx](https://nx.dev) used to create project workspace
* [pnpm v6](https://pnpm.io/motivation) to save disk space
* [Angular framework v12](https://angular.io/)
* [ckan](https://ckan.org/) open source data management system for powering data hubs and data portals - [github repo](https://github.com/ckan/ckan)
* [Node module luxon](https://www.npmjs.com/package/luxon) for dates and times, including [Interval](https://moment.github.io/luxon/docs/class/src/interval.js~Interval.html) time between two [DateTimes](https://moment.github.io/luxon/docs/class/src/datetime.js~DateTime.html)
* [ngrx Component Store](https://ngrx.io/guide/component-store) stand-alone library that helps to manage local/component state and ensures error state is handled so effect not broken
* [ngrx tapResponse](https://ngrx.io/api/component-store/tapResponse) handles the response in ComponentStore effects in a safe way
* [ngrx updater](https://ngrx.io/guide/component-store/write) i mutable state changes
* [rxjs Timer operator](http://reactivex.io/documentation/operators/timer.html) observable to emit a particular item after a given delay
* [Github Actions](https://github.com/actions) - to be able to include Continous Integration (CI) and continuous deployment (CD) capabilities and many other features directly in the repository - [explained by Gabriel Tanner](https://gabrieltanner.org/blog/an-introduction-to-github-actions)
* [Denmark CO2 Emission stats](https://www.energidataservice.dk/collections/co2-emission)
* [regular expressions](https://regex101.com/) testing online
* [Polyfill.io](https://polyfill.io/v3/) browser feature polyfills

## :floppy_disk: Setup

* Install dependencies using `npm i`
* Run `nx dep-graph` to see a diagram of the dependencies of your projects.
* Run `nx serve angular-ngrx-energy` for a dev server. Frontend will open at
  `http://localhost:4200/` - refreshes on code changes
* Run `npm run lint` to lint test entire client-side codebase using TSLint.
* Run `nx build angular-ngrx-energy` to generate a build file

## :wrench: Testing

* tba

## :computer: Code Examples

* f

```typescript

```

## :cool: Features

* f

## :clipboard: Status, Testing & To-Do List

* Status: in work. Video 4 1hr23m
* Testing: not tested yet
* To-Do: complete

## :clap: Inspiration/General Tools

* Lars Gyrup Brink Nielsen: Youtube: Angular After Dark:
* [Nx After Dark: Setting up an Angular 12 workspace](https://www.youtube.com/channel/UCsZWzmsdKz2VA49XXBK5TQA)
* [Nx After Dark: Creating a data access library with NgRx Component Store](https://www.youtube.com/watch?v=4z6anukUjPk)
* [Nx After Dark: Implementing and testing data access with NgRx Component Store and Angular HTTP](https://www.youtube.com/watch?v=om3hhlCtgz4)
* [Nx After Dark: Adding a date-time library and testing an RxJS timer](https://www.youtube.com/watch?v=bKgXFUnHKvU&t=767s)
* [European Network of Transmission System Operators for Electricity website](https://www.entsoe.eu/)
* [Node Time](https://nodatime.org/) alternative date and time API for .NET.
* [Joda Time](https://www.joda.org/joda-time/) replacement for the Java date and time classes.
* [Fireship: Nx Quickstart - How to Scale a JavaScript Project](https://www.youtube.com/watch?v=VUyBY72mwrQ)

## :file_folder: License

* N/A

## :envelope: Contact

* Repo created by [ABateman](https://github.com/AndrewJBateman), email: gomezbateman@yahoo.com
