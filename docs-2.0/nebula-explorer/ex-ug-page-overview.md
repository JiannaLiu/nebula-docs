# Page overview

This topic introduces the Nebula Explorer page to help you learn more about Nebula Explorer's functions.

The Nebula Explorer page consists of three modules top navigation bar, left-side navigation bar, and canvas. 

![explorer-overview](https://docs-cdn.nebula-graph.com.cn/figures/explorer-overview_en.png)

## Top navigation bar

| Icon/Element                                                    | Description                                                 |
| ------------------------------------------------------------ | ---------------------------------------------------- |
| **Explorer**                                                 | Visually explore and analyze data. For more information, see [Start querying](ex-ug-query-exploration.md), [Vertex Filter](node-filtering.md), and [Graph exploration](ex-ug-graph-exploration.md).     |
| **Visual Query**                                             | Visually construct scenarios for data queries. For more information, see [Visual Query](12.query-visually.md).          |
| ![create_schema](https://docs-cdn.nebula-graph.com.cn/figures/studio-nav-schema.png) | Manage Nebula Graph database graph spaces. For more information, see [Create a schema](10.create-schema.md).       |
| ![import_data](https://docs-cdn.nebula-graph.com.cn/figures/studio-btn-download.png) | Bulk import of data into Nebula Graph. For more information, see [Import data](11.import-data.md).          |
| ![Console](https://docs-cdn.nebula-graph.com.cn/figures/nav-console2.png) | Query the Nebula Graph data with nGQL statements. For more information, see [Console](explorer-console.md). |
| ![language](https://docs-cdn.nebula-graph.com.cn/figures/navbar-language.png) | Select the language of  Nebula Explorer page. Chinese and English are supported.   |
| ![help](https://docs-cdn.nebula-graph.com.cn/figures/navbar-help.png) | Guide and help you in using Nebula Graph.          |
| ![clear_connection](https://docs-cdn.nebula-graph.com.cn/figures/image-icon10.png) | Show the Nebula Graph version and allow you to disconnect from Nebula Explorer.    |

## Left-side navigation bar

!!! note

    After logging into Explorer, select a graph space and click on it to unlock query and exploration functions in the left-side navigation bar. For more information, see [Choose graph spaces](13.choose-graphspace.md).

Click the icons in the left-side navigation bar to import, analyze, and explore graph data. The descriptions of the icons are as follows:

| Icon  | Description |
| ----- | ---- |
| ![query](https://docs-cdn.nebula-graph.com.cn/figures/nav-query2.png) | Enter VIDs or tags to query data. For more information, see [Ways to query data](ex-ug-query-exploration.md).     |
| ![filter](https://docs-cdn.nebula-graph.com.cn/figures/nav-filter.png) | Search for target vertexes displayed on the canvas. For more information, see [Filter vertices](node-filtering.md).     |
| ![expand](https://docs-cdn.nebula-graph.com.cn/figures/nav-expand.png) | Perform explorations on the vertices on the canvas by setting edge directions, steps, and filtering conditions. For more information, see [Graph exploration](ex-ug-graph-exploration.md).   |
| ![commonNeighbor](https://docs-cdn.nebula-graph.com.cn/figures/nav-commonNeighbor.png) | Select at least two vertices on the canvas to search for their common neighbors. For more information, see [Graph exploration](ex-ug-graph-exploration.md).    |
| ![findPath](https://docs-cdn.nebula-graph.com.cn/figures/nav-findPath.png) | Find all paths, the shortest path, and the non-loop paths from the source to the destination vertex. For more information, see [Graph exploration](ex-ug-graph-exploration.md).    |
| ![propertyView](https://docs-cdn.nebula-graph.com.cn/figures/nav-propertyView.png) | Choose whether to display the properties of vertices or edges on the canvas. For more information, see [Graph exploration](ex-ug-graph-exploration.md).    |
| ![snapshot](https://docs-cdn.nebula-graph.com.cn/figures/snapshot-history.png) | View historical snapshots. For more information, see [Canvas snapshots](canvas-operations/canvas-snapshot.md).     |
| ![graphSpace](https://docs-cdn.nebula-graph.com.cn/figures/nav-graphSpace.png) | View all graph spaces. Click a graph space to create a canvas corresponding to it. For more information, see [Choose graph spaces](13.choose-graphspace.md).    |
| ![Help](https://docs-cdn.nebula-graph.com.cn/figures/nav-help.png) | View Explorer documents and Nebula Graph forum.     |
| ![Setup](https://docs-cdn.nebula-graph.com.cn/figures/nav-setup2.png) | View your account, explorer version and shortcuts, limit returned results.|

## Canvas

!!! note

    After logging into Explorer, select a graph space and click on it to enter the canvas page. For more information, see [Choose graph spaces](13.choose-graphspace.md).

Graph data can be displayed visually on a canvas. The canvas consists of the following parts:

- Tabs on the Top
- Visualization modes
- Data storage
- Search box
- Layouts
- Minimap
- Data overview

For more information, see [Canvas overview](canvas-operations/canvas-overview.md).