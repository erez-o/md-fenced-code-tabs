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

## Non Interapted - two laguages:

```cpp
ecs_entity_t e = ecs_new_cpp(world, 0);
```
```c
ecs_entity_t e = ecs_new_c(world, 0);
```

## Non Interapted - three laguages:

```cpp
ecs_entity_t e = ecs_new_cpp(world, 0);
```
```c
ecs_entity_t e = ecs_new_c(world, 0);
```
```java
ecs_entity_t e = ecs_new_java(world, 0);
```

## Non Interapted - four laguages, two in the same language:

```cpp
ecs_entity_t e = ecs_new_cpp(world, 0);
```
```c
ecs_entity_t e = ecs_new_c1(world, 0);
```
```c
ecs_entity_t e = ecs_new_c2(world, 0);
```
```java
ecs_entity_t e = ecs_new_java(world, 0);
```

