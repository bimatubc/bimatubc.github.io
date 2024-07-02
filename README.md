# The Official Webpage for BIMatUBC

Don't forget to copy .env.example to .env

Yeah I'm bad at documenting stuff, will improve later on -- Nabil

## How to write a blog

1. Copy `src/views/Blogs/BlogExample.vue` to `src/views/Blogs/blog_name.vue`
2. Edit `blog_name.vue`
3. Add the routing in `src/router/blogRoutes.js`
4. Add basic blog data to `src/data/blogposts.js`
5. Push your changes to github
6. Deploy to github pages with `bun gh:deploy`
