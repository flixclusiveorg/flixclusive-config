Feel free to fetch and get me

# Contribution

**REMINDER: Please do not touch the `app.json` file!**

Home items and Search items consist of the following JSON object:
```
// This can be called as a Catalog or Category object.

{
   "name": "Trending Now",
   "type": "all",
   "required": true,
   "canPaginate": true,
   "query": "trending/all/day?language=en-US"
}
```

Object properties:
	- `name` - The name of the category
	- `type` - The type of category [`all` | `movie` | `tv`]. Use `all` if it has category item for movie and tv.
	- `required` - Makes this category to be loaded as a necessity.
	- `canPaginate` - Makes this category  paginateable
	- `query` - the path + query of the TMDB API. **DO NOT INCLUDE THE HOST HERE!**