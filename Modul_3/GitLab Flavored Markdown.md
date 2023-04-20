<p>Гитлаб использует <a href="https://gitlab.com/gitlab-org/gitlab-ce/blob/master/doc/user/markdown.md#header-ids-and-links">GitLab Flavored Markdown (GFM)</a></p>
<p>здесь "все уцененные заголовки автоматически получают идентификаторы"</p>
<p>можно использовать мышь :</p>

<ul>
<li>наведите указатель мыши на заголовок</li>
<li>наведите курсор мыши на селектор наведения, который становится видимым слева от заголовка</li>
<li>
<p>скопировать и сохранить ссылку с помощью правой кнопки мыши</p>
<p>например в README.md файл у меня есть заголовок:</p>
</li>
</ul>

<p><code>## series expansion formula of the Boettcher function</code></p>
<p>что дает ссылку : </p>
<blockquote>
<p><a href="https://gitlab.com/adammajewski/parameter_external_angle/blob/master/README.md#series-expansion-formula-of-the-boettcher-function">https://gitlab.com/adammajewski/parameter_external_angle/blob/master/README.md#series-expansion-formula-of-the-boettcher-function</a></p>
</blockquote>

<p>префикс может быть удален, поэтому ссылка здесь просто </p>
<pre><code class="hljs stylus">file<span class="hljs-selector-id">#header</span>
</code></pre>
<p>что означает:</p>
<pre><code class="hljs ada">README.md#series-expansion-formula-<span class="hljs-keyword">of</span>-the-boettcher-<span class="hljs-keyword">function</span>
<span class="hljs-title"></span></code></pre>
<p>теперь его можно использовать как:</p>
<p><code>[series expansion formula of the Boettcher function](README.md#series-expansion-formula-of-the-boettcher-function)</code></p>
<p>можно сделайте это вручную: замените пробелы знаком дефиса. </p>
<p>живой пример-это <a href="https://gitlab.com/ValenHouse/Apple/blob/main/README.md">здесь</a></p> 