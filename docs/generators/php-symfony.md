---
title: Config Options for php-symfony
sidebar_label: php-symfony
---

| Option | Description | Values | Default |
| ------ | ----------- | ------ | ------- |
|sortParamsByRequiredFlag|Sort method arguments to place required parameters before optional parameters.| |true|
|sortModelPropertiesByRequiredFlag|Sort model properties to place required parameters before optional parameters.| |true|
|ensureUniqueParams|Whether to ensure parameter names are unique in an operation (rename parameters that are not).| |true|
|allowUnicodeIdentifiers|boolean, toggles whether unicode identifiers are allowed in names or not, default is false| |false|
|prependFormOrBodyParameters|Add form or body parameters to the beginning of the parameter list.| |false|
|modelPackage|package for generated models| |null|
|apiPackage|package for generated api classes| |null|
|variableNamingConvention|naming convention of variable name, e.g. camelCase.| |snake_case|
|invokerPackage|The main namespace to use for all classes. e.g. Yay\Pets| |null|
|packageName|The main package name for classes. e.g. GeneratedPetstore| |null|
|srcBasePath|The directory to serve as source root.| |null|
|artifactVersion|The version to use in the composer package version field. e.g. 1.2.3| |null|
|composerVendorName|The vendor name used in the composer package name. The template uses {{composerVendorName}}/{{composerProjectName}} for the composer package name. e.g. yaypets| |null|
|bundleName|The name of the Symfony bundle. The template uses {{bundleName}}| |null|
|bundleAlias|The alias of the Symfony bundle. The template uses {{aliasName}}| |null|
|composerProjectName|The project name used in the composer package name. The template uses {{composerVendorName}}/{{composerProjectName}} for the composer package name. e.g. petstore-client| |null|
|hideGenerationTimestamp|Hides the generation timestamp when files are generated.| |true|
|phpLegacySupport|Should the generated code be compatible with PHP 5.x?| |true|

## IMPORT MAPPING

| Type/Alias | Imports |
| ---------- | ------- |


## INSTANTIATION TYPES

| Type/Alias | Instantiated By |
| ---------- | --------------- |
|array|array|
|map|map|


## LANGUAGE PRIMITIVES

<ul data-columns="2" style="list-style-type: disc;-webkit-columns:2;-moz-columns:2;columns:2;-moz-column-fill:auto;column-fill:auto"><li>number</li>
<li>void</li>
<li>bool</li>
<li>string</li>
<li>array</li>
<li>double</li>
<li>byte</li>
<li>mixed</li>
<li>float</li>
<li>int</li>
<li>object</li>
</ul>

## RESERVED WORDS

<ul data-columns="2" style="list-style-type: disc;-webkit-columns:2;-moz-columns:2;columns:2;-moz-column-fill:auto;column-fill:auto"><li>die</li>
<li>callable</li>
<li>declare</li>
<li>isset</li>
<li>use</li>
<li>queryparams</li>
<li>echo</li>
<li>do</li>
<li>while</li>
<li>unset</li>
<li>empty</li>
<li>resourcepath</li>
<li>endwhile</li>
<li>protected</li>
<li>continue</li>
<li>else</li>
<li>elseif</li>
<li>function</li>
<li>endfor</li>
<li>trait</li>
<li>catch</li>
<li>if</li>
<li>case</li>
<li>new</li>
<li>static</li>
<li>var</li>
<li>require</li>
<li>require_once</li>
<li>list</li>
<li>formparams</li>
<li>headerparams</li>
<li>_header_accept</li>
<li>include_once</li>
<li>exit</li>
<li>as</li>
<li>eval</li>
<li>extends</li>
<li>final</li>
<li>try</li>
<li>httpbody</li>
<li>implements</li>
<li>private</li>
<li>const</li>
<li>for</li>
<li>global</li>
<li>interface</li>
<li>__halt_compiler</li>
<li>_tempbody</li>
<li>switch</li>
<li>foreach</li>
<li>default</li>
<li>goto</li>
<li>public</li>
<li>array</li>
<li>and</li>
<li>xor</li>
<li>class</li>
<li>include</li>
<li>or</li>
<li>endswitch</li>
<li>break</li>
<li>enddeclare</li>
<li>abstract</li>
<li>instanceof</li>
<li>print</li>
<li>throw</li>
<li>insteadof</li>
<li>clone</li>
<li>namespace</li>
<li>endif</li>
<li>endforeach</li>
<li>return</li>
</ul>
