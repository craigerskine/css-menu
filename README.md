# css-menu
Pure CSS multi-menu navigation system with hover persistence

* Up to 4 levels (3 sub menus)
* Horizontal and Vertical
* Centering
* Plays nice with frameworks like [Superfish](https://github.com/joeldbirch/superfish/)

### Usage

* Use a nested unordered list structure as your nav with a class of `nav-menu` on the root `ul`. Add a `nav-vertical` class if you want stacked nav.

### Example

````
<ul class="nav-menu">
  <li><a href="..">Home</a></li>
  <li><a href=".." class="nav-active">Products</a>
    <ul>
      <li><a href="..">Some Product</a></li>
      ..
    </ul>
  </li>
  <li><a href="..">Contact</a></li>
  ..
</ul>