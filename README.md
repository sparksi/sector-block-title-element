# Sector Block Title Element

Change your Drupal block title elements to a HTML element of your choice.

## Usage

```block.html.twig

{% if label %}
    <{{ title_element | default('strong') }}{{ title_attributes.addClass('block-title') }}>
    {{ label }}
    </{{ title_element | default('strong') }}>
  {% endif %}

```