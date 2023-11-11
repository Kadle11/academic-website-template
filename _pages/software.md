---
title: "Code"
layout: gridlay
sitemap: false
permalink: /code/
---

<style>
img{
  border-radius: 10px;
}
iframe {
  width: 175px;
  display: inline;
  vertical-align:middle;
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- border: 1px solid red; -->
}
.col-md-3 {
  margin:0;
  padding:0;
  margin-top:10px;
  margin-bottom:10px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  height: auto;
  float: none;
  background:white;
  border-radius:20px;
  <!-- border: 1px solid black; -->
}
</style>

### Performance Analysis

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>Jaeger Aggregator</b></h4>
<!-- <a href="https://example.com" target="_blank"><button class="btn btn-success btn-sm">WEBSITE</button></a> -->
<a href="https://github.com/Kadle11/JaegerRequestAnalysis" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a>
<!-- <a href="{{ site.url }}{{ site.baseurl }}/papers/example_proceeding.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a>  -->

<!-- <b>Authors:</b>
<i>Example authors</i> -->

<ul>
<li>Tool to help analyze time spent in each process recorded by jaegertracing/jaeger:all-in-one container.</li>
<li>Code retrieves multiple requests and computes cumulative metrics unavailable on Jaeger.</li>
<li>Helps determine performance bottlenecks in the latency profile of an application.</li>
</ul>

</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>Configurable CPU Heatmap Generator</b></h4>
<!-- <a href="https://example.com" target="_blank"><button class="btn btn-success btn-sm">WEBSITE</button></a> -->
<a href="https://github.com/Kadle11/CPU_Heatmap" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a>
<!-- <a href="{{ site.url }}{{ site.baseurl }}/papers/example_proceeding.pdf" target="_blank"><button class="btn btn-danger btn-sm">PAPER</button></a>  -->

<!-- <b>Authors:</b>
<i>Example authors</i> -->

<ul>
<li>Tool to help visualize CPU utilization for any workload.</li>
<li>Code retrieves data using linux SAR and visualizes data using Python's Seaborn Library.</li>
</ul>

</div>
</div>
</div>

### Systems/Applications

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>Distributed Fault-Tolerant Sharded KV Store</b></h4>
<!-- <a href="https://example.com" target="_blank"><button class="btn btn-success btn-sm">WEBSITE</button></a> -->
<!-- <a href="https://github.com/Kadle11/CPU_Heatmap" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a> -->
<a href="/reports/sharded_kv_store.pdf" target="_blank"><button class="btn btn-danger btn-sm">DESIGN DOC</button></a> 

<!-- <b>Authors:</b>
<i>Example authors</i> -->

<ul>
<li> Sharded KV Store that supports shard reconfiguration and cross-shard transactions.</li>
<li> Shards are replicated across multiple servers in a ‘Shard-Group’ that uses Paxos to maintain linearizability. </li>
<li> Shard reconfigurations balance load on Shard-Groups and support the addition/removal of replica groups. </li>
</ul>

</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-12 col-sm-12">
<h4><b>Dynamic Resource Allocation for Microservice Applications</b></h4>
<a href="/reports/dynamic_alloc_ppt.pdf" target="_blank"><button class="btn btn-success btn-sm">SLIDES</button></a>
<!-- <a href="https://github.com/Kadle11/CPU_Heatmap" target="_blank"><button class="btn btn-info btn-sm">GIT</button></a> -->
<a href="/reports/dynamic_alloc.pdf" target="_blank"><button class="btn btn-danger btn-sm">DESIGN DOC</button></a> 

<!-- <b>Authors:</b>
<i>Example authors</i> -->

<ul>
<li> Built a pipeline to identify SLO violations based on the <a href="https://www.usenix.org/conference/osdi20/presentation/qiu" target="_blank"> FIRM paper </a>. </li>
<li> Critical Component Extractor determines probable microservices responsible for SLO violations. </li>
<li> AIMD and RL-based agents reallocate CPU shares on the fly to mitigate the SLO violations </li>
</ul>

</div>
</div>
</div>