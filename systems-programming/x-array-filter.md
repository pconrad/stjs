{% if include.problem %}

Fill in the blank in the code below so that it runs correctly.
Note: you can compare strings in JavaScript using `<`, `>=`, and other operators,
so that (for example) `person.personal > 'P'` is `true`
if someone's personal name starts with a letter that comes after 'P' in the alphabet.

{% include multi pat='x-array-filter/filter.*' fill='js txt' %}

{% else %}

FIXME: write solution

{% endif %}
