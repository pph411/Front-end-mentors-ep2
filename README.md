## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Screenshot](./images/Screenshot-NFT-preview-card%20from-FM.JPG)

### Links

- Solution URL: [https://codepen.io/pph411/pen/bGQVgyW]

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- A try of semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I've found a bit hard to figured out how to make the overlay but it was easy after all.

```html
<p>
  <span class="eth-logo"
    ><img src="./images/icon-ethereum.svg" alt="Ethereum logo"
  /></span>
  0.041 ETH
</p>
```

```css
.overlay {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  background-color: cyan;
  border-radius: 10px;
  overflow: hidden;
  width: 100%;
  height: 300px;
  opacity: 0;
  transition: 0.5s ease;
}

.container:hover .overlay {
  opacity: 0.6;
  height: 300px;
}

.icon {
  color: white;
  font-size: 20px;
  position: absolute;
  top: 55%;
  left: 50%;
  transform: translate(-50%, -50%);
  opacity: 0;
}

.container:hover .icon {
  opacity: 1;
}
```

### Continued development

I'm not sure if the estructure is fine and i'm still had a hard time to center all but i will get better.

### Useful resources

- [imgur](https://imgur.com/) - This helped me to have images on my solution on codepen.

## Author

- Frontend Mentor - [@pph411](https://www.frontendmentor.io/profile/pph411)
