<h1 align="center">🐍 GitHub Python Code Snippet Scraper 🐍</h1>

<p align="center">
  <img alt="GitHub" src="https://img.shields.io/github/license/<your-github-username>/<your-repo-name>?style=flat-square">
  <img alt="Python Version" src="https://img.shields.io/badge/python-3.8%2B-blue?style=flat-square">
</p>

<p>📝 This script scrapes the GitHub API for Python code snippets and generates a dataset of valid Python code snippets in CSV format.</p>

<h2>🚀 Usage</h2>

<ol>
  <li>Clone the repository and navigate to the root directory.</li>
  <li>Install the required Python packages with the following command:<br><code>pip install -r requirements.txt</code></li>
  <li>Run the script with the following command:<br><code>python scraper.py --output dataset.csv --limit 200</code></li>
</ol>

<h2>📜 Arguments</h2>

<p>The script supports the following arguments:</p>

<table>
  <tr>
    <th>Argument</th>
    <th>Description</th>
    <th>Default Value</th>
  </tr>
  <tr>
    <td><code>--output</code></td>
    <td>The name of the output CSV file.</td>
    <td><code>dataset.csv</code></td>
  </tr>
  <tr>
    <td><code>--limit</code></td>
    <td>The maximum number of code snippets to generate.</td>
    <td><code>200</code></td>
  </tr>
</table>

<h2>📦 Required Packages</h2>

<p>The script requires the following Python packages:</p>

<ul>
  <li><a href="https://docs.python-requests.org/en/latest/">requests</a></li>
  <li><a href="https://docs.python.org/3/library/argparse.html">argparse</a></li>
  <li><a href="https://docs.python.org/3/library/base64.html">base64</a></li>
  <li><a href="https://docs.python.org/3/library/ast.html">ast</a></li>
  <li><a href="https://docs.python.org/3/library/csv.html">csv</a></li>
</ul>

<h2>👨‍💻 Contribution</h2>

<p>If you find a bug or have a suggestion, feel free to open an issue or submit a pull request.</p>

<h2>📄 License</h2>

<p>Released under the MIT license.</p>
