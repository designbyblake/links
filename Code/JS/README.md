# CSS

## Keep Sidebar in same location between page loads

[Source Tweet](https://twitter.com/hakimel/status/1262337514741706752)
```JS
let sidebar = document.querySelector( '.sidear' );
let top = localStorage.getItem( 'sidebar-scroll' );
if(top !== null) {
	sidebar.scrollTop = parseInt( top, 10 );
}

window.addEventListener( 'beforeunload', () => {
	localStorage.setItem( 'sidebar-scroll', sidebar.scrollTop);
} );
```
