A Jupyter notebook caculator for finding which "incomplete" proteins should be combined and in what ratios to give a more balanced [EAA](https://en.wikipedia.org/wiki/Essential_amino_acid) profile.

**This is not medical or dietery advice! I have no qualification and have only done internet research. If I have gotten something wrong, please let me know!**

Feel free to add more foods/mess around with the target EAAs in the notebook itself. Click show code and edit the data, then click "Run all" in the top bar. If you find any intresting new protein sources please raise an issue so I can add them.  

Only combinations that have a PDCAAS of <90% are shown, these are considered "complete" proteins and you could get your recomened ammount of all EAAs from just this source.  
Results are as follows:
|index|Protein1|Protein2|Optimized Combined Score \([PDCAAS](https://en.wikipedia.org/wiki/Protein_digestibility_corrected_amino_acid_score)\)|Whole Food Ratio by weight \(Approximate\)|% Calories from Protein \(Approximate\)|
|---|---|---|---|---|---|
|17|Lentils|Seitan|96\.65050643363003|2\.4 parts Lentils to 1 part Seitan|44\.3%|
|13|Seitan|Green Peas|103\.4782600278402|0\.2 parts Seitan to 1 part Green Peas|36\.7%|
|14|Beans|Seitan|101\.07123696111265|4\.6 parts Beans to 1 part Seitan|36\.4%|
|16|Beans|Peanuts|96\.73144404364739|2\.0 parts Beans to 1 part Peanuts|20\.8%|
|18|Peanuts|Lentils|93\.67666188219144|0\.9 parts Peanuts to 1 part Lentils|20\.5%|
|15|Peanuts|Green Peas|97\.95081729529545|0\.4 parts Peanuts to 1 part Green Peas|20\.4%|
|9|Beans|Corn|107\.61346576261792|0\.8 parts Beans to 1 part Corn|20\.3%|
|12|Corn|Lentils|104\.89594867007193|2\.3 parts Corn to 1 part Lentils|19\.8%|
|7|Corn|Green Peas|110\.66915974788462|1\.0 parts Corn to 1 part Green Peas|19\.7%|
|1|Beans|Buckwheat|117\.70114836993409|0\.5 parts Beans to 1 part Buckwheat|17\.2%|
|3|Buckwheat|Green Peas|117\.33490509175715|1\.4 parts Buckwheat to 1 part Green Peas|17\.1%|
|5|Beans|Quinoa|116\.20647505760478|0\.1 parts Beans to 1 part Quinoa|17\.0%|
|6|Quinoa|Green Peas|115\.90628710070877|4\.8 parts Quinoa to 1 part Green Peas|17\.0%|
|0|Lentils|Buckwheat|117\.981071565113|0\.3 parts Lentils to 1 part Buckwheat|16\.8%|
|4|Quinoa|Lentils|116\.32818450984168|13\.2 parts Quinoa to 1 part Lentils|16\.7%|
|2|Oats|Buckwheat|117\.69177579858369|0\.4 parts Oats to 1 part Buckwheat|14\.2%|
|10|Rice|Beans|107\.4029062642252|2\.1 parts Rice to 1 part Beans|13\.7%|
|8|Rice|Green Peas|110\.02304011814003|1\.7 parts Rice to 1 part Green Peas|13\.2%|
|11|Rice|Lentils|105\.07315479741108|4\.0 parts Rice to 1 part Lentils|12\.5%|
