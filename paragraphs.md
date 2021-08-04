# $modules array

```
public static $modules = [
    [...]
    'paragraphs',
];
```

# setUp()

```
$this->installConfig(['paragraphs']);
```

For entity schema, paragraph without an 's'.

```
$this->installEntitySchema('paragraph');
```

# Create a paragraph bundle

I usualy use a feature, but you can do this programmatically

@TODO

# Create a paragraph

Like any other entity

```
$paragraph = Paragraph::create([
  'type' => 'paragraph_bundle', // <- replace with yout own bundle
  'field_partner' => 'My partner', <- replace with you own fields
  'field_message' => 'Message for my entity',
]);
$paragraph->save();
```
