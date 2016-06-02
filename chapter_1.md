# chapter 1

## Section 1

Some content
Here is an inline code example `imread`
Here is some multiline  code
```MATLAB
for i=1:100;
i;
end
```
{% exercise %}
Define a variable `x` equal to 10.
{% initial %}
var x =
{% solution %}
var x = 10;
{% validation %}
assert(x == 10);
{% context %}
// This is context code available everywhere
// The user will be able to call magicFunc in his code
function magicFunc() {
    return 3;
}
{% endexercise %}
