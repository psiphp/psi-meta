# Psi {{ item.title }}

[![Build Status](https://travis-ci.org/psiphp/{{ item.name }}.svg?branch=master)](https://travis-ci.org/psiphp/{{ item.name }})
{% if item.styleci is defined %}
[![StyleCI](https://styleci.io/repos/{{ item.styleci }}/shield)](https://styleci.io/repos/59910930)
{% endif %}
{% if item.has_packagist is defined and item.has_packagist %}
[![Latest Stable Version](https://poser.pugx.org/psiphp/{{ item.name }}/version.png)](https://packagist.org/packages/psiphp/{{ item.name }})
[![Total Downloads](https://poser.pugx.org/psiphp/content-type/d/total.png)](https://packagist.org/packages/psiphp/{{ item.name }})
{% endif %}

This component is part of the Psi Content Management Framework

{{ lookup('file', 'README-' ~ item.name ~ '.md') }}

## Documentation

You can find out more about this component and others
[here](https://readthedocs.org/psiphp).

## Installation

Require in `composer.json`:

```bash
$ composer require 'psiphp/{{ item.name }}'
```

## Contributing

Just go ahead and create a PR, you know you need to.

