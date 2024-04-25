# Image gallery

> A simple food menu project

## Table of contents

- [Image gallery](#image-gallery)
  - [Table of contents](#table-of-contents)
  - [General info](#general-info)
  - [Screenshots](#screenshots)
  - [Technologies](#technologies)
  - [Setup](#setup)
  - [Code Examples](#code-examples)
  - [Status](#status)

## General info

> The objective of the project is to practice separation of concern in
> JavaScript.

## Screenshots

![food menu](./assets/food-menu.png)

## Technologies

- JavaScript
- HTML5
- CSS3
- VSC code

## Setup

clone the repo and npm install and start live server

## Code Examples

```js
const loadHandler = () => {
	data.buttons.forEach((btnData) => {
		const { id, text } = btnData;
		const button = createButton('button', 'btn', id, text);
		dom.btnContainer.append(button);
	});

	data.menu.forEach((item) => {
		const createDom = createCard(item);
		dom.cardContainer.append(createDom);
	});
};

export default loadHandler;
```

## Status

Project is: _done_
