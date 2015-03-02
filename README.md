## Summary ##

Shows how trying to size an `md-icon` using an iconset fails when jquery is included in the page.

## Building ##

1. Check out project
2. Run `npm install`
3. Run `npm run server`
4. Open browser and go to: http://localhost:8080/index.html (See how icons are sizing. This page contains NO jquery).
5. Now go to http://localhost:8080/index_broken.html (See how icons do **NOT** size due to inclusion of jquery).

## Differences between HTML files ##

The only difference in the two .html pages is the inclusion of jquery in the broken page:

```html
<script src="https://code.jquery.com/jquery-2.1.3.min.js"></script>
```
