# AlmaviaStandard

This is a custom phpcs sniff that finds "Novactive" namespace and replace it by the [new one](https://github.com/tdjebali/AlmaviaStandard/blob/main/Sniffs/Namespaces/DisallowOldNamesapceSniff.php#L12).

## How to use

Clone this repo then execute the following command in your project:

``phpcs --standard=PATH/TO/AlmaviaStandard /path/TO/SRC``

or

``phpcbf --standard=PATH/TO/AlmaviaStandard /path/TO/SRC``
