<h1>Numerical Matrix Analysis Tool</h1>


<h2>Description</h2>
<p>This project utilizes Numpy to perform statistical analysis on a 3x3 matrix. It provides mean, variance, standard deviation, max, min, and sum for insights into the numerical distribution.</p>

<h2>Environment & Libraries Used</h2>
<ul>
  <li><b>Python</b></li>
  <li><b>NumPy</b></li>
</ul>

<h2>Program Walk-through:</h2>

<h3>Convert List to Matrix</h3>
<pre><code>matrix = np.array(numbers).reshape(3, 3)</code></pre>

<h3>Calculate Statistical Metrics</h3>
<pre><code>
result = {
  'mean': [np.mean(matrix, axis=0).tolist(), np.mean(matrix, axis=1).tolist(), np.mean(matrix).item()],
  'variance': [np.var(matrix, axis=0).tolist(), np.var(matrix, axis=1).tolist(), np.var(matrix).item()],
  ...
}
</code></pre>

<h2>Output Example</h2>
<pre><code>{
  'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  'variance': [[6.0, 6.0, 6.0], [0.6666666666666666, 0.6666666666666666, 0.6666666666666666], 6.666666666666667],
  ...
}</code></pre>

<h2>Conclusion</h2>
<p>This tool assists in understanding the underlying patterns in numerical data through matrix analysis, enhancing data-driven decision-making.</p>
