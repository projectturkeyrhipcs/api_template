### Унифицированные ресурсы


```json
{
	'meta': {
		'_link': {
			'self': {'href': url},
			'next': {'href': url},
			'relation_name_1': {'href': url},
			...
		},
		'_type_resource': 'индифицированный',
	}
	'data': {
			'this' : {
				...
			},
			'relation': {
				"relation_name_1": [
					{
						'rel':[]
					}
				],
				"relation_name_2": [
					{
						'rel':[]
					}
				],
				"relation_name_3": [
					{
						'rel':[]
					}
				],
				...
			}
		}
	'references': {
			'name_category_for_select1': [
				{
					'rel':[]
				}
			],
			'name_category_for_select2': [],
			...
		}
}
```

### Не унифицированные

```json
{
	'meta': {
		'_link': {
			'self': {'href': url},
			'next': {'href': url},
			'relation_name_1': {'href': url},
			...
		},
		'_type_resource': 'индифицированный',
	}
	'data': {
			'this' : [{
					...
					'relation': {
						"relation_name_1": [
							{
								...
								'rel':[]
							}
						],
						"relation_name_2": [
							{
								...
								'rel':[]
							}
						],
						"relation_name_3": [
							{
								...
								'rel':[]
							}
						],
						...
					}
				},
			},
			...
		]
	'references': {
			'name_category_for_select1': [
				{
				    ...
					'rel':[]
				}
			],
			'name_category_for_select2': [
				{
				    ...
					'rel':[]
				}
			],
			...
		}
}
```


Дополнительная информация:
- https://gist.github.com/kevinswiber/3066768