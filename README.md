# bootstrap-accordion-filter
Accordion filter, with matching alert div

<h1>Accordion Filter Div</h1>
		<h2>Properties</h2>
		<table class="table table-hover"
			id="accordionFilterProp"
			data-toggle="table"
			data-mobile-responsive="true">
			<thead>
			<tr>
				<th>Attribute</th>
				<th>Type</th>
				<th>Description</th>
			</tr>
			</thead>
			<tr>
				<td>data-toggle</td>
				<td>String</td>
				<td>Activate Accordion Filter without using JavaScript</td>
			</tr>
			<tr>
				<td>data-url</td>
				<td>String</td>
				<td>The url to get the json to build the filters</td>
			</tr>
			<tr>
				<td>data-msgDiv</td>
				<td>String</td>
				<td>If this is set, then the checked values will be displayed in the div with the indicated id</td>
			</tr>
		</table>
		
		<h2>Accordion Alerts Div</h2>
		<table class="table table-hover"
			id="divProp"
			data-toggle="table"
			data-mobile-responsive="true">
			<thead><tr>
				<th>Attribute</th>
				<th>Type</th>
				<th>Default</th>
				<th>Description</th>
			</tr></thead>
			<tr>
				<td>data-msg</td>
				<td>String</td>
				<td>Items</td>
				<td>The alert message will say Displaying {data-msg} for:</td>
			</tr>
		</table>
		
		<h2>Accordion Filter Methods</h2>
		<p>The calling method syntax: <code>$(&#39;#sidebarGroupAccordion&#39;).accordionFilter(&#39;method&#39;, parameter);</code>.</p>

		<table class="table table-hover"
			id="accordionMethods"
			data-toggle="table"
			data-mobile-responsive="true">
			<thead>
				<tr>
					<th>Name</th>
					<th>Description</th>
				</tr>
			</thead>
			
			<tr>
				<td>filterData</td>
				<td>Get an associative array with the indexes of the checked boxes.</td>
			</tr>
			
		</table>
		
		<h2>Accordion Filter Events</h2>
		<p>	To use event syntax:</p>

		<div class="highlight">
			<pre><code class="language-js" data-lang="js"><span class="nx">$</span><span class="p">(</span><span class="s1">'#sidebarGroupAccordion'</span><span class="p">).</span><span class="nx">on</span><span class="p">(</span><span class="s1">'af.fd.changed'</span><span class="p">,</span> <span class="kd">function</span> <span class="p">(</span> <span class="p">)</span> <span class="p">{</span>
    <span class="c1">// ...</span>
<span class="p">});</span>
</code></pre>
</div>
		<table class="table table-hover"
			id="accordionEvents"
			data-toggle="table"
			data-mobile-responsive="true">
			<thead>
				<tr>
					<th>Name</th>
					<th>Description</th>
				</tr>
			</thead>
			
			<tr>
				<td>"af.fd.changed"</td>
				<td>Get an associative array with the indexes of the checked boxes.</td>
			</tr>
			
		</table>
