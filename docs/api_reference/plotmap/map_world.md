# PlotMap.map_world(*res*=*'l'*)

It creates a map of the world and saves into 'm'.

Parameters | Description | Type
--- | --- | ---
res | Resolution of boundary database to use. Can be c (crude), l (low), i (intermediate), h (high), f (full) or None. If None,  no boundary data will be read in (and class methods such as draw coastlines will raise an if invoked). Higher res datasets are much slower to draw. | str, 'l', 'i', 'h', 'f'

Return to the [PlotMap Index](index_plotmap.md).
