# Donut Shop App

Mobile app for ordering a single donut developed with React.

## Table of contents

- [General info](#general-info)
- [Technologies](#technologies)
- [Features](#features)
- [Setup](#setup)
- [Project Status](#project-status)
- [Acknowledgements](#acknowledgements)

## General Info

Mobile app for ordering a donut. The main goal of this project was to get familiar with React, implement the provided design as close as possible and complete the project on deadline given by [boom.dev](https://boom.dev).

You can find the design [here](https://www.figma.com/file/ruQOaYl4FwXdpndvDtaTQH/Untitled?node-id=1%3A2&t=tMxGpOBbD6kx2x92-0)

## Technologies

Project is created with:

- React
- React Router

## Features

- When the user clicks on the “Start” button on the StartScreen, the app switches to MenuScreen.
- Donuts in the MenuScreen rotate.
- When the user selects a donut from the menu, the app switches to PaymentScreen.
- When the user clicks on one of the Pay buttons, the app switches to PreparationScreen.
- On the preparation screen the selected donut from the menu is rotating.
- The donut is in preparation for 5 sec, after that the app switches to ReadyScreen.
- When the user clicks on the “Done” button in the ReadyScreen, the app switches to StartScreen.

## Setup

To run this project, install it locally using npm:

```
$ npm install
$ npm start
```

## Project Status

Project is: _completed_

## Acknowledgements

This project is based on the [Boom Dev React Development Track](https://boom.dev).
