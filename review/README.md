# Review

Re Norman's video, the key to fear/happiness and thinking is that fear causes focused, depth-first thinking and happiness causes breadth-first thinking. Exactly right on the three ways good design makes us happy.

On IA with regard to search, the key point is that it inverts the tree. Instead of users coming in on the home page and drilling down to the page they want, they tend to come in on the page they want, and, if necessary, drill down to the home page. Thus we have a sort of "multiple homepage" effect. Remember this?

Good grasp of PACE layering!

On IxD, when we say "the best designs don't exist", what we mean is that when design is done right, it becomes invisible to the user. They just *use it*. They don't notice the design or think about how to use it. It's just effortless.

That is the sine qua non of great design. Do we ever reach that point? Rarely. But a person can dream, right?

What happened to your example of a bad affordance in the physical world? The one I always think of first (because it's so common) is pull handles on doors that must be pushed. The proper affordance for "push" is a flat panel for your palm. If you sit by a door with a bad affordance, you'll see people screwing it up all day long. Sometimes they'll even give up thinking the door is locked!

Why architects refuse to learn from this is one of those mysteries of the universe. We may never know. :-)

On URLs, I'm a little confused by the crawl budget bit. Essentially, crawling (indexing) a website takes time which equals resources (more computers required, more energy used, etc.). So Google limits the amount of resources it will expend on a site. If your site is more complicated than it needs to be, you'll just be wasting that budget and your site may not be updated in Google's index as often or as thoroughly as you'd want. Does that make sense?

On the form.html, please don't provide HTML snippets. Entire pages, from DOCTYPE through the closing `</html>` tag, please.

For one thing, it is difficult to validate the HTML without the rest of the page. For another, get used to making full pages while you can. Good practice.

But because you provide a snippet, I'm guessing that you didn't validate. That's not good. I did validate your form, and I got several errors. You could have avoided these if you used the [validator](https://validator.w3.org/#validate_by_input). So use it! Every time. :-)

For example:

1. Error: No space between attributes at line 4.
2. Error: Attribute is not allowed on element input at this point at line 8.
3. Error: End of file seen when expecting text or an end tag at line 40.
4. Error: Unclosed element textarea at line 14.
5. Error: Unclosed element fieldset at line 10.
6. Error: Unclosed element form at line 1.
7. Error: End of file seen and there were open elements, line 40.
8. Error: The for attribute of the label element must refer to a non-hidden form control, line 8.

Remember that the `for` attribute points to the `id` attribute of the input, not the `name`. Some of these errors are carry-forward from earlier errors. Try running your page through the validator and see if you can fix it. Slack me if you need help.

Nice work on the CSS selectors, on the different accessibility testers (funny how they are somewhat different, isn't it?), and on the usability. Keep it up.

Wow! Really nice effort on the job stories. You have a great future as a *full stack* web developer. :-)

On the site structure, please export your draw.io diagrams as PNGs. My sight reading of SVG files (binary at that) is pretty weak. :-) Or take a screenshot.

On your JSPM app, be sure to add a `.gitignore` file in your root folder with the following in it:

```
node_modules/
jspm_packages/
```

I've added it for you. You don't want to version other people's code on your GitHub repo. Just takes up space for no reason. Sorry, this was my bad. Forgot to mention that in the lesson plan. (It's so automatic that we tend to forget these things.)

There were some other problems as well. Did you actually make this work in the browser? I ask because you didn't have ramda.js installed. You need to install it with:

```sh
jspm install npm:ramda
```

Then the file works. Also, delete the `main.js` file in your jspmapp folder as it's confusing.

The code itself is nice, but there's not much of it. Do you feel comfortable with these functions? If not, ping me on Slack and I'm happy to answer questions.

Overall, you're keeping the pace well. I know it's a lot of work, but you'll be glad for it when you get on site&mdash;only a few weeks away now! Are you excited?

So keep it up. And thanks for the effort.

