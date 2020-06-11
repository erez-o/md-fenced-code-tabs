# Examples

## Interapted:

cpp example

```cpp
ecs_entity_t e = ecs_new_cpp(world, 0);
```

C example

```c
ecs_entity_t e = ecs_new_c(world, 0);
```

## Non Interapted

## Simple two languages:

```cpp
ecs_entity_t e = ecs_new_cpp(world, 0);
```
```c
ecs_entity_t e = ecs_new_c(world, 0);
```

### Additional Options:

Without a specificed language, the tab name turns into tab 'txt'

To control the tab name, use raw html and write `<pre><code class="lang tab_name">...</code></pre>`

```cpp
ecs_entity_t e = ecs_new_cpp(world, 0);
```
```c
ecs_entity_t e = ecs_new_c(world, 0);
```
```
ecs_entity_t e = ecs_new_java(world, 0);
```
<pre><code class="cpp tab_name">
ecs_entity_t e = ecs_new_java(world, 0);
</code></pre>


### Inside a list:
<ul>
<li>
<pre><code class="cpp">ecs_entity_t e = ecs_new_cpp</code></pre>
<pre><code class="c">ecs_entity_t e = ecs_new_c</code></pre>
</li>
</ul>
