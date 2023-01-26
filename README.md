# msr23-artifact
Generalizable Python code change patterns - MSR 2023 paper artifact


<table>
<thead>
	<tr>
		<th>#</th>
		<th>Trend</th>
		<th>Pattern group</th>
    <th># of patterns</td>
    <th># of generalizable patterns (%)</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td style="text-align:right">1</td>
		<td rowspan="8">Move to with statement and context manager</td>
		<td>Read, write, traverse data</td>
    <td style="text-align:right">135</td>
    <td style="text-align:right">29 (21%)</td>
	</tr>
	<tr>
		<td style="text-align:right">2</td>
		<td>Disable or enalbe gradient calculation</td>
    <td style="text-align:right">27</td>
    <td style="text-align:right">0 (0%)</td>
	</tr><tr>
		<td style="text-align:right">3</td>
		<td>Swap ML tranining device</td>
    <td style="text-align:right">5</td>
    <td style="text-align:right">0 (0%)</td>
	</tr>
  <tr>
		<td style="text-align:right">4</td>
		<td>Change name and variable scopes in DL networks</td>
    <td style="text-align:right">30</td>
    <td style="text-align:right">0 (0%)</td>
	</tr>
  <tr>
		<td style="text-align:right">5</td>
		<td>Execute dependencies of Tensorflow graphs</td>
    <td style="text-align:right">16</td>
    <td style="text-align:right">1 (6%)</td>
	</tr>
  <tr>
		<td style="text-align:right">6</td>
		<td>Temporarily change configurations of ML libraries</td>
    <td style="text-align:right">7</td>
    <td style="text-align:right">1 (14%)</td>
	</tr>
  <tr>
		<td style="text-align:right">7</td>
		<td>Move to context managers in pytest</td>
    <td style="text-align:right">85</td>
    <td style="text-align:right">4 (5%)</td>
	</tr>
  <tr>
		<td style="text-align:right">8</td>
		<td>Open temporary directory</td>
    <td style="text-align:right">28</td>
    <td style="text-align:right">2 (7%)</td>
	</tr>
</tbody>
</table>
