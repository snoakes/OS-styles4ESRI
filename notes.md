<b>NOTES:</b><br>
This mxd is designed for the following scales:
<ul>
<li>1:1,000,000</li>
<li>1:500,000</li>
<li>1:250,000</li>
<li>1:125,000</li>
<li>1:64,000</li>
<li>1:32,000</li>
<li>1:16,000</li>
<li>1:8,000</li>
<li>1:4,000</li>
<li>1:2,000</li>
</ul>
NB. The 1:2,000 scale can also be used to create larger scales in a map cache e.g. 1:1,000, 1:500 & 1:250


In Cornwall, other local datasets were also used:
<ul>
<li>Town points - used to label smaller settlements for the 250K, 125K & 64K scale levels</li>
<li>Places - used to label water features for the 64K scale level</li>
<li>Coastline area - created from the Strategi coastline features and used as a land fill for the 1M, 500K, 250K, 125K 
& 64K scale levels</li>
<li>Sea extent - created from the Strategi coastline features and used as a sea fill for the 1M, 500K, 250K, 125K, 64K 
& 32K scale levels</li>
</ul>
These layers have been removed from the mxd.


<b>Labelling:</b><br>
The labelling has been created using Maplex, so ensure that the option to use the Maplex labelling engine is switched on.<br>

VectorMap Local specifies the rotation of the text in tenths of a degree. Create a new integer field in the data called 
Rotation and populate it with the values divided by 10 and rounded.

Using the tools in ArcGIS, convert the labels to annotation.  Create a second copy of the mxd, remove all the labelling 
and source the labels from these newly created annotation layers.  This mxd can now be used to create an ArcGIS Server 
map cache.

<b>Final note:</b> This was designed for Cornwall which is predominantly rural in nature. It may need tweaking to get 
the best results for an more urban area.  If you make changes and/or improvements, please share them back again.
