<p align="center">
	<img src="images/jigtime.png?raw=true" width="400" /><br>
	<a href="https://jigtime.org" target="_blank">https://jigtime.org</a>
</p>

### Natural JavaScript module for SPA (Single Page Application)

<p align="center"><img src="images/spa.png?raw=true" width="702" /></p>

### Interacting with separated SPA resources

<p align="center"><img src="images/resolver.png?raw=true" width="850" /></p>

### JavaScript-based template engine support

<p align="center"><img src="images/template_engine.png?raw=true" width="490" /></p>

```
HTML SPA resource templates are rendered directly in JigTime (Natural JavaScript) on the front-end, but JS/CSS templates and static HTML page templates are transpiled on the back-end via deno.
```

<p align="center"><img src="images/transpile.png?raw=true" width="490" /></p>

### Path-based SPA resource management

<table>
	<tbody>
		<tr>
			<td><b>Request</b></td>
			<td><code>/path/to/path:</code> SPA resource ID</td>
		</tr>
		<tr>
			<td><b>Response</b></td>
			<td>
				<code>/path/to/path.pug:</code> HTML SPA resource by pug<br>
				<code>/path/to/path.less:</code> CSS SPA resource by less<br>
				<code>/path/to/path.ts:</code> JS SPA resource by ts
			</td>
		</tr>
	</tbody>
</table>

### Flexible history Management

<p align="center"><img src="images/history.png?raw=true" width="550" /></p>

### Provide various widgets

```
chipsinput, chipsselect, dataframe, datasheet, dialog, editor, grid, labelinput, loading, popup, resizabletext, tree, win, winup
```

### Provide various extensions

```
colorx, datex, matrixx, papaparsex, timex, valuex
```

### Support theme (eye-protect, light, dark)

<p align="center"><img src="images/theme.png?raw=true" width="820" /></p>

### Development independent of back-end platform

```
To avoid becoming a module dependent on a specific back-end platform, the back-end support module is separated from JigTime. JigBack is a back-end support module of JigTime, and supports Oak middleware framework, PHP, Spring boot, Servlet/JSP, JAX-RS, and supports data-binding, MVC development, etc.

In JigBack, JS/CSS templates and static HTML page templates are transpiled via deno. When TypeScript, LESS, SCSS, and static HTML page templates are transpiled via deno, they are converted into executable templates on the front-end. When operating on a server, only transpiled templates can be deployed, so deno is no longer needed.
```

<p align="center">
	<img src="images/jigback.png?raw=true" width="234" /><br>
	<a href="https://jigback.org" target="_blank">https://jigback.org</a>
</p>