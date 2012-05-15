# Stylus Sugar

When you're ready to have awesome syntax highlighting for Stylus in Espresso, all you need to do is pull up Terminal and type the following:

```bash
cd ~/Library/Application\ Support/Espresso/Sugars
git clone git://github.com/bluestrike2/Bluestrike2-Stylus.sugar.git
```

# Some Basics

For the most part, this is pretty much a straight port of the Textmate bundle aside from a few minor tweaks for Espresso's regex limitations.

I tried to get code folding support, but as of this release, have had no such luck given the lack of closing brackets etc. for Stylus (not that I'm complaining; far from it) to base it off of. I'd appreciate any ideas anyone has on coming up with a decent solution there. Beyond that, I did however add folding support for the following frankenstein creation:

```
// @group GROUP NAME HERE
.... your super awesome css
// @end
```

It's basically just a particularized comment, but I'm hoping that it'll at least offer some benefit to people out there when it comes to organization until I can better wrangle 

# Todo

- Placeholder theme
- Get Itemizers functioning smoothly (not included right now)
- Add CodeSense Support for auto-completion, etc.
- Clean up syntax zone naming as needed
- Considering adding the ability to convert to .css but to be honest, you're better off just using [Codekit](http://incident57.com/codekit) if that's what you need. 

If you're interested in making improvements to this sugar, feel free to do so and submit a pull request.