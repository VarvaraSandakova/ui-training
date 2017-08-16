# ui-training

### feature-1
Create 'User' constructor function and implement following interface
```javascript
function User {
  // ...
}

const u = new User();

u.setName(name);
u.getName();
u.setName(name).getName();
```
### feature-2

Create 'BookmarkView' class which takes such arguments:
  * url: string
  * imagePath: string
  * description: string

And implement following interface:

```javascript
function BookmarkView(url, imagePath, description) {
	this.template = ``; // should be used for creating documentFragment

	this.render = function (){
		// should return documentFragment based on the template
	}
}

const bookmarkView = new BookmarkView(url, imagePath, description);

const bookmark = bookmarkView.render();

document.body.appendChild(bookmark); // should render bookmark in the DOM
```
