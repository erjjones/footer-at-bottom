footer-at-bottom
================

Sample web site to demonstrate how to set a footer to the bottom of a page for all views

## Set footer to bottom of the page

```
<body>
	<div id="wrap">
		<!-- Put all body html here -->
	</div>
	<div id="footer">
		<!-- Put all footer html here -->
	</div>
</body>
```

```
/* Wrapper for page content to push down footer */
#wrap {
  min-height: 100%;
  height: auto;
  /* Negative indent footer by its height */
  margin: 0 auto -60px;
  /* Pad bottom by footer height */
  padding: 0 0 60px;
}

/* Set the fixed height of the footer */
#footer {
  height: 60px;
  border-top: 1px solid #e5e5e5;
  background-color: #f9f9f9;
}
```

## Follow Me

+ http://twitter.com/erjjones

## Copyright and license

Licensed under the MIT License (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the COPYING file.

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.