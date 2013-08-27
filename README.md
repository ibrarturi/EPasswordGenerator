EPasswordGenerator Yii Extension
=================================

YII Framework extension for generating password based on the provided parameters


This Yii framework extension by default will return 8 characters long password and you can also provide optional parameters
to make the password more complex.



**Requirements**

Tested with Yii 1.1.10 and 1.1.12. may work on other versions

**Installation**

* Extract the file under protected/extensions folder.
* In main.php file:

```
'components' => array(
....
	'epassgen' => array(
            'class' => 'ext.epasswordgenerator.EPasswordGenerator',
        ),
....
```

**Default Usage**

```
$passowrd = Yii::app()->epassgen->generate();
```

**Usage with optional parameters**

```
$passowrd = Yii::app()->epassgen->generate(10, 2, 3, 2);
```
