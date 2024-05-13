---
title: Results
layout: home
---

<table align="center" width=800px border="1" style="border-collapse: collapse; border: 0.5px solid black; margin: auto; text-align: center">
    <caption>Results of NeFL for CIFAR-10 dataset under <b>IID</b> (left) and <b>non-IID</b> (right) settings are presented: Top-1 classification accuracies (%) for the worst-case submodel and the average of the performance of five submodels.</caption>
    <tr>
        <th rowspan="3"><b>Model</b></th>
        <th rowspan="3"><b>Method</b></th>
        <th colspan="2"><b>IID</b></th>
        <th colspan="2"><b>non-IID</b></th>
    </tr>
    <tr>
        <th><b>Worst</b></th>
        <th><b>Avg</b></th>
        <th><b>Worst</b></th>
        <th><b>Avg</b></th>
    </tr>
    <tr>
    </tr>
    <tr>
        <th rowspan="4">ResNet18</th>
        <td>HeteroFL</td>
        <td>80.62 (&plusmn; 0.24)</td>
        <td>84.26 (&plusmn; 1.95)</td>
        <td>76.25 (&plusmn; 1.05)</td>
        <td>80.11 (&plusmn; 2.03)</td>
    </tr>
    <tr>
        <td>FjORD</td>
        <td>85.12 (&plusmn; 0.22)</td>
        <td>87.32 (&plusmn; 1.21)</td>
        <td>75.81 (&plusmn; 5.65)</td>
        <td>77.99 (&plusmn; 6.50)</td>
    </tr>
    <tr>
        <td>DepthFL</td>
        <td>64.80 (&plusmn; 10.49)</td>
        <td>82.44 (&plusmn; 10.17)</td>
        <td>59.61 (&plusmn; 5.16)</td>
        <td>76.89 (&plusmn; 9.60)</td>
    </tr>
    <tr>
        <td><b>NeFL (ours)</b></td>
        <td><b>86.86 (&plusmn; 0.22)</b></td>
        <td><b>87.88 (&plusmn; 0.68)</b></td>
        <td><b>81.26 (&plusmn; 2.44)</b></td>
        <td><b>81.71 (&plusmn; 3.14)</b></td>
    </tr>
    <tr>
        <th rowspan="4">ResNet34</th>
        <td>HeteroFL</td>
        <td>79.51 (&plusmn; 0.44)</td>
        <td>83.16 (&plusmn; 1.96)</td>
        <td>76.03 (&plusmn; 1.34)</td>
        <td>79.63 (&plusmn; 5.24)</td>
    </tr>
    <tr>
        <td>FjORD</td>
        <td>85.12 (&plusmn; 0.25)</td>
        <td>87.36 (&plusmn; 1.19)</td>
        <td>74.70 (&plusmn; 3.66)</td>
        <td>76.01 (&plusmn; 5.24)</td>
    </tr>
    <tr>
        <td>DepthFL</td>
        <td>25.73 (&plusmn; 4.25)</td>
        <td>75.30 (&plusmn; 24.88)</td>
        <td>30.42 (&plusmn; 9.34)</td>
        <td>70.76 (&plusmn; 21.04)</td>
    </tr>
    <tr>
        <td><b>NeFL (ours)</b></td>
        <td><b>87.71 (&plusmn; 0.37)</b></td>
        <td><b>89.02 (&plusmn; 0.80)</b></td>
        <td><b>80.76 (&plusmn; 2.82)</b></td>
        <td><b>83.31 (&plusmn; 2.94)</b></td>
    </tr>
</table>