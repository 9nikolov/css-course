TLDR: 
Achieving a Masonry Gallery Layout, where column number changes from 1 to 2 to 3 to 4, based on media breakpoints is hard, it requires a lot of JS / alternatively people use ready made Masonry Layout Libraries. 
Much easier solution is CSS Columns.

Pixabay appears to employ Flexbox for the Masonry Layout in its gallery. Yet, through hands-on experience attempting to construct a gallery page with a masonry layout that adjusts columns from 1 to 2 to 3 to 4 based on @media breakpoints, I discovered that Flexbox falls short in flexibility for a Masonry Layout Gallery requiring a variable number of columns based on breakpoints.

My hypothesis is that Pixabay omitted the 3-column layout for precisely this reason—it necessitates a considerable amount of dynamically generated HTML code through JavaScript, and so forth. I also have the impression that they might not have been aware that achieving a Masonry Gallery Layout could be significantly easier using CSS Columns.

Despite the availability of tools/frameworks that handle masonry layouts, it appears that Pixabay did not choose to use such a framework in this instance.

Currently, I am a beginner making efforts to grasp the fundamentals of CSS, 
so there's a possibility I could be wrong in my observation.