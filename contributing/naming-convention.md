## Naming convention

**language independent convention**:'

This is the naming convention that must be followed for all most of the programming languages used in this repository

1. Give meaningful names. Names must be a little more descriptive not more than 25 characters long

2. Add meaningful comments when/where necessary

3. Leave 2 lines between classes and  2 lines between functions for readibility.

<br/>

**Python**: 
Follow PEP-8 guidlines.

**JavaScript**:

1. camelCased names for functions.
2. No semicolons, unless you are writing inline code.

**react-query library naming convention**

You are to follow these convention when using the react-query hooks.

[react-query docs](https://react-query-v3.tanstack.com/reference/useQuery)

1. if youe using useQuery, useQueries - suffix your name with Query eg: `const usersQuery = useQuery([''])`

2. use an array to provide query key as this will help us fussy update the cache later

3. for mutation suffix the name with Mutate eg: `updateUserMutate = useMutation()`
