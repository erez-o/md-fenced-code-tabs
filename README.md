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

### Three laguages:

```cpp
ecs_entity_t e = ecs_new_cpp(world, 0);
```
```c
ecs_entity_t e = ecs_new_c(world, 0);
```
```java
ecs_entity_t e = ecs_new_java(world, 0);
```

### Four laguages, two in the same language, one not defined:

```cpp
ecs_entity_t e = ecs_new_cpp(world, 0);
```
```c
ecs_entity_t e = ecs_new_c1(world, 0);
```
```c
ecs_entity_t e = ecs_new_c2(world, 0);
```
```
ecs_entity_t e = ecs_new_java(world, 0);
```

### Inside a list:
<ul>
<li>
<pre><code class="cpp">ecs_entity_t e = ecs_new_cpp</code></pre>
<pre><code class="c">ecs_entity_t e = ecs_new_c</code></pre>
</li>
</ul>
