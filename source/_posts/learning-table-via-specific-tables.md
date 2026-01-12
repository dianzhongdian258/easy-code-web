---
title: earning table via specific tables
date: 2026-01-12 13:50:37
tags: col 
        scope
        rowspan
---
<table>
<tbody>
<tr>
<th scope="col">specie</th>
<th scope="col">Name</th>
<th scope="col">Age</th>
</tr>

<tr>
<th rowspan="3" scope="row">dog</th>
<td>Nora</td>
<td>5</td>
</tr>

<tr>
<th scope="row">Gino</td>
<td>2</td>
</tr>

<tr>
<td>Lulu</td>
<td>10</td>
</tr>

<tr>
<th scope="row">cat</th>
<td>Elizabeth</td>
<td>6</td>
</tr>
</tbody>
</table>

what we should notice carefully is the attribute "rowspan",when rowspan=3,the "dog"occupied  space where three seperate,empty table cells(<td></td>) were supposed to be 
