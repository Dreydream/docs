<!--
  _____   ____    _   _  ____ _______   ______ _____ _____ _______ 
  |  __  / __   |  | |/ __ __   __| |  ____|  __ _   _|__   __|
  | |  | | |  | | |  | | |  | | | |    | |__  | |  | || |    | |   
  | |  | | |  | | | . ` | |  | | | |    |  __| | |  | || |    | |   
  | |__| | |__| | | |  | |__| | | |    | |____| |__| || |_   | |   
  |_____/ ____/  |_| _|____/  |_|    |______|_____/_____|  |_|   
  This file is auto-generated by script/generate_graphql_api_content.sh,
  please build the schema.json by running `rails api:graph:export`
  with https://github.com/buildkite/buildkite/,
  replace the content in data/graphql_data_schema.json
  and run the generation script `./scripts/generate-graphql-api-content.sh`.
-->
<!-- vale off -->
<h1 class="has-pills" data-algolia-exclude>
  Annotation
  <span class="pill pill--object pill--normal-case pill--large"><code>OBJECT</code></span>
</h1>
<!-- vale on -->


<p>An annotation allows you to add arbitrary content to the top of a build page in the Buildkite UI</p>


{:notoc}

<table class="responsive-table responsive-table--single-column-rows">
  <thead>
    <th>
      <h2 data-algolia-exclude>Fields</h2>
    </th>
  </thead>
  <tbody>
    <tr><td><h3 class="is-small has-pills"><code>body</code><a href="/docs/apis/graphql/schemas/object/annotationbody" class="pill pill--object pill--normal-case pill--medium" title="Go to OBJECT AnnotationBody"><code>AnnotationBody</code></a></h3><p>The body of the annotation</p></td></tr><tr><td><h3 class="is-small has-pills"><code>context</code><a href="/docs/apis/graphql/schemas/scalar/string" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR String"><code>String</code></a></h3><p>The context of the annotation that helps you differentiate this one from others</p></td></tr><tr><td><h3 class="is-small has-pills"><code>createdAt</code><a href="/docs/apis/graphql/schemas/scalar/datetime" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR DateTime"><code>DateTime</code></a></h3><p>The date the annotation was created</p></td></tr><tr><td><h3 class="is-small has-pills"><code>id</code><a href="/docs/apis/graphql/schemas/scalar/id" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR ID"><code>ID</code></a></h3></td></tr><tr><td><h3 class="is-small has-pills"><code>style</code><a href="/docs/apis/graphql/schemas/enum/annotationstyle" class="pill pill--enum pill--normal-case pill--medium" title="Go to ENUM AnnotationStyle"><code>AnnotationStyle</code></a></h3><p>The visual style of the annotation</p></td></tr><tr><td><h3 class="is-small has-pills"><code>updatedAt</code><a href="/docs/apis/graphql/schemas/scalar/datetime" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR DateTime"><code>DateTime</code></a></h3><p>The last time the annotation was changed</p></td></tr><tr><td><h3 class="is-small has-pills"><code>uuid</code><a href="/docs/apis/graphql/schemas/scalar/id" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR ID"><code>ID</code></a></h3><p>The public UUID for this annotation</p></td></tr>
  </tbody>
</table>




<h2 data-algolia-exclude>Interfaces</h2>
<a href="/docs/apis/graphql/schemas/interface/node" class="pill pill--interface pill--normal-case pill--large" title="Go to INTERFACE Node"><code>Node</code></a>