<table><tr>
<th width="33.3%">Map</th><th width="33.3%">View</th><th width="33.3%">Layers</th>
</tr><tr>
<td><p>A [map](ol.Map.html) is made of [layers](ol.layer.html), a [view](ol.View.html) to visualize them, [interactions](ol.interaction.html) to modify map content and [controls](ol.control.html) with UI components.</p>
[Overview](ol.Map.html)<br>
[Creation](ol.Map.html#Map)<br>
[Events](ol.MapBrowserEvent.html)</td>
<td><p>The view manages the visual parameters of the map view, like resolution or rotation.</p>
[ol.View](ol.View.html) with center, projection, resolution and rotation</td>
<td><p>Layers are lightweight containers that get their data from [sources](ol.source.html).</p>
[ol.layer.Tile](ol.layer.Tile.html)<br>
[ol.layer.Image](ol.layer.Image.html)<br>
[ol.layer.Vector](ol.layer.Vector.html)<br>
[ol.layer.VectorTile](ol.layer.VectorTile.html)</td>
</tr><tr>
<th>Controls</th><th>Interactions</th><th>Sources and formats</th>
</tr><tr>
<td>[Map default controls](ol.control.html#defaults)<br>
[All controls](ol.control.html)
</td>
<td>
[Map default interactions](ol.interaction.html#defaults)<br>
Interactions for [vector features](ol.Feature.html)
<ul><li>[ol.interaction.Select](ol.interaction.Select.html)</li>
<li>[ol.interaction.Draw](ol.interaction.Draw.html)</li>
<li>[ol.interaction.Modify](ol.interaction.Modify.html)</li></ul>
[All interactions](ol.interaction.html)</td>
<td>[Tile sources](ol.source.Tile.html) for [ol.layer.Tile](ol.layer.Tile.html)
<br>[Image sources](ol.source.Image.html) for [ol.layer.Image](ol.layer.Image.html)
<br>[Vector sources](ol.source.Vector.html) for [ol.layer.Vector](ol.layer.Vector.html)
<br>[Vector tile sources](ol.source.VectorTile.html) for [ol.layer.VectorTile](ol.layer.VectorTile.html)
<br>[Formats](ol.format.Feature.html) for reading/writing vector data
<br>[ol.format.WMSCapabilities](ol.format.WMSCapabilities.html)</td></tr>
<tr><th>Projections</th><th>Observable objects</th><th>Other components</th></tr>
<tr><td><p>All coordinates and extents need to be provided in view projection (default: EPSG:3857). To transform, use [ol.proj.transform()](ol.proj.html#transform) and [ol.proj.transformExtent()](ol.proj.html#transformExtent).</p>
[ol.proj](ol.proj.html)</td>
<td><p>Changes to all [ol.Objects](ol.Object.html) can observed by calling the [object.on('propertychange')](ol.Object.html#on) method.  Listeners receive an [ol.ObjectEvent](ol.ObjectEvent.html) with information on the changed property and old value.</p>
<td>[ol.DeviceOrientation](ol.DeviceOrientation.html)<br>
[ol.Geolocation](ol.Geolocation.html)<br>
[ol.Overlay](ol.Overlay.html)<br></td>
</tr></table>
