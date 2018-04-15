# [scroll](https://testpolygon.github.io/scroll/)

I use html `{ width: 100vw; overflow-x: hidden; }` to locate a content regardless of the existence of the scrollbar.
And I use -webkit CSS tags to make a custom scrollbar. `::-webkit-scrollbar { width: 12px; } ::-webkit-scrollbar-thumb { background-color: #bbb; }`
I have set background of body tag to blue color.

You can see that after manipulations, the text is behind the left border of the screen (That says that the body tag has been moved to the left. It's problem.), and under the scrollbar is the html background (That says that the html tag has not moved.).

And in the mobile view, after reloading the page, the html tag width becomes more than 100%. On a real mobile device, there is no such problem.
