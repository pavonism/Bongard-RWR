# Bongard-RWR 

One of the interesting research avenues is to compare the MLLMs performance on synthetic BPs vs.
real-world ones. Note, however, that a direct performance comparison on synthetic Bongard dataset
vs. real-world Bongard HOI and Bongard-OpenWorld datasets is not meaningful, as these datasets
depict different concepts. To enable a meaningful comparison and additionally determine whether
the MLLMs performance score is domain-related, we introduce Bongard Real-World Representations, a focused dataset that expresses concepts present in synthetic BPs using real-world images,
thus creating their real-life equivalents, as seen in the examples below, which present **LEFT**: Triangles. **RIGHT**: Quadrangles. 

<table>
    <td width="50%">
        <img src="https://www.foundalis.com/res/bps/bongard/p010.gif"/>
    </td>
    <td>
        <img src="dataset/10/whole-white.png"/>
    </td>
</table> 

The file <a href="Side_by_Side_Comparison_To_Synthetic_Bongard.pdf">Side_by_Side_Comparison_To_Synthetic_Bongard</a> presents a side-by-side comparison between corresponding Bongard and Bongard-RWR instances. All translated examples can be found in the <a href="dataset">/dataset</a> folder.