
```php
<?php
Kirki::add_field( 'my_config', array(
	'type'        => 'typography',
	'settings'    => 'my_setting',
	'label'       => esc_attr__( 'Control Label', 'kirki' ),
	'section'     => 'my_section',
	'default'     => array(
		'font-family'    => 'Roboto',
		'variant'        => 'regular',
		'font-size'      => '14px',
		'line-height'    => '1.5',
		'letter-spacing' => '0',
		'subset'         => array( 'latin-ext' ),
		'color'          => '#333333',
		'text-transform' => 'none',
		'text-align'     => 'left'
	),
	'priority'    => 10,
	'output'      => array(
		array(
			'element' => 'body',
		),
	),
) );
?>
```