Run `npx serve -l 3000` and `npx serve -l 3001` from the plainjs directory.

Browse to localhost:3000/index.html.  Click the button in either iframe to observe it updating the other via direct DOM access via `window.frames[otherIframeName].document.getElementById("received").textContent = "message"`.
