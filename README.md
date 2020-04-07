# Example Event Delegation

Here is a basic example of how you can apply events to multiple elements.

---

You only need to listen the entire document.

`document.addEventListener('click', function (event) { YOUR LOGIC  }, false);`

Then inside the function you just need to work with the event, in this case we are going to use a conditional. If event is equal of any div with class name 'btn' we are goint to change the background.


`   if (event.target.matches('.btn')) {
    console.log(event.target)
    event.target.style.background = "#fdc72e"
    msn.innerHTML = event.target.id
}`