A Base rule is applied to an element using an element selector, a descendent selector, or a child selector, along with any pseudo-classes. It doesn’t include any class or ID selectors. It is defining the default styling for how that element should look in all occurrences on the page.

Base styles include setting heading sizes, default link styles, default font styles, and body backgrounds. There should be no need to use !important in a Base style.

It is highly recommended that you specify a body background. Some users may define their own background as something other than white. If you work off the expectation that the background will be white, your design may look broken. Worse, your font colour choice may clash with the user’s setting and make your site unusable.