PHPHtml-Optimizer w/Enhancer v1.0 (support Optimizer 1.3.1.2 ++)


|Function        | Method         |  Description   |  Parameters                   |  
|:---            |:---            |:---            |:---                           |
| `send_to()`    | `send_to()`    | redirect to    |url       |
| `view_to()`    | `view_to()`    | template file  |DIR/KEY/filename |
| `bring_to()`    | `bring_to()`  | get file       |DIR/KEY/filename/Extension/INCLUDES/INCLUDES_ONCE/REQUIRE |
| `isbelongs()`   | `belongs_to()` | send file into page ? |PageName/KeyFolderPath/__KEY_FOLDER_PATH__/'keyFolderPath' |
| `getKeyPath()`   | `GetKeyFolderPath()` | get page? folder key | none |
| `__BR()`   | `BREAK()` | Html `<Br/>` tag | FUNC_ASSOC/METHOD_ASSOC/CLASS_ASSOC |
| `__HR()`   | `LINE()` | Html `<hr/>` tag | FUNC_ASSOC/METHOD_ASSOC/CLASS_ASSOC |
| `__space()`   | `SPACE()` | Space string | none |
| `MERGE()`   | `MERGE()` | Make ELEM/ELEMENTS Once at the time| none |
| `SetFileExT()`   | `SetFileExtension() ` | Set file extention | `__PHP__`,` __HTML__ `,`__CSS__`,`__JS__`,`__JPG__`,`__JPEG__`,`__PNG__`,`__GIF__`, ` __BMP__`, `__TEX__`,`__XLS__`,`__XLSX__`,`__DOCX__`, `__DOCX__`,`__PPT__`,`__PPTX__`,`__ODT__`, `__TXT__`, `__RTF__` |
| `SetElemAttr()`   | `SetElemAttr()` | Set Elements HTML custom attr | ['attrName'],['attrValue'] |
| `DOIF()`   | `__magicIF()` | append version of IF statements design for optimizer inline | Condition[Bool]/Result __NOTE:__ Not support Global variable use Ternary IF instead |
| `DOELSE()`   | `__magicELSE()` | append version of IFELSE statements design for optimizer inline | Condition[Bool]/DefaultValue/Result  __NOTE:__ Not support Global variable use Ternary IF instead|
| `PERFORM()`   | `PERFORM()` | Execute Association Optimizer Method/Function | MethodsOrFunctions/FUNC_ASSOC/METHOD_ASSOC/CLASS_ASSOC |
| `STRING()`   | `STRING()` | Print "String" without Element | strings/FUNC_ASSOC/METHOD_ASSOC/CLASS_ASSOC |
| `ATTR()`   | `ATTR()` | Html Header body template | META / TITLE / LINK / SCRIPT / CUSTOM_END / BEGIN_CUSTOM_END |
| `ELEM()`   | `ELEM()` | Custom HTML Elements/Tags | ElemName/Value/ElemAttr/ElemId/ElemClass |
| `GETFROM()`   | `GETFROM()` | Directory/Path Cleaner parameter of bring_to,view_to  | DIR/KEY/ ` bring_to(GETFROM(['PATH','inc']), 'hero', __PHP__);` `view_to()` |
| `SET_DIR_PATH()`   | `SET_DIR_PATH()` | Path/Dir/Ruri - registration holder | folder-file-directory, LOCALHOST |

__directories.php__ file register file currently support : PATH | DIR | RURI, make your code clean and safe. 

```PHP
<?php $Care = NEW \PHPHtml\CodeOptimizer\optimizer\Enhancers();  ?>
<?php 
/*
|
| Register Current PATH 
|--------------------------------------------------------------------------
|
*/
$PATH['REGISTERED'] = [
 
 // live version
 'inc' => SET_DIR_PATH('includes'),
 
 // Localhost version 
 'inc' => SET_DIR_PATH('includes', LOCALHOST)

];

/*
|
| Register Current DIR / VIEW Templates
|--------------------------------------------------------------------------
|
*/
$VIEWS['REGISTERED'] = [
 
  'Views'        => SET_DIR_PATH('saver/views'),
  'VTemplates'   => SET_DIR_PATH('saver/views/templates')        

];

/*
|
| Register Current RURI / LOCALHOST
|--------------------------------------------------------------------------   
|
*/
$RURI['REGISTERED'] = [
  
  // For LocalHost 
  'redirect'   => SET_DIR_PATH('404')     

];

```

For Installation / Configuration <a href="https://github.com/nielsofficeofficial/PHPHtml-Optimizer-Installations"> Process link here </a><br /> 
For PHPOptimizer more examples and <a href="https://github.com/nielsofficeofficial/PHPHtml-Optimizer-Docx"> Documentation link here </a><br /> 
For PHPMaintenance Mode and <a href="#"> SOON on <i>PHPHtml-Optimizer</i> v1.4 </a><br />
For PHPForm and <a href="#"> SOON on <i>PHPHtml-Optimizer</i> v1.4 </a><br /> 
For Html to PHPHtml-Optimizer Generator(Converter) <a href="#"> SOON <i> Convert HTML to PHPHtml-Optimizer Premium</i></a><br /> 
For Developer <a href="https://github.com/nielsofficeofficial/PHPHtml-Optimizer/issues"> Support link here </a><br /> 
This Library is 100% secured and fully free ready to use, If you see vulnerability you can email me: @ nieldigitalsolution@gmail.com

<h2>Thanks To:</h2>
<h5>
Github : To allow me to upload my PHPHtml-Optimizer PHP Library to repository<br /> 
php.net : To oppurtunity Develop web application using corePHP - PHPFrameworks<br />
w3school : HTML Elements reference</h5>

__For Suggestion and Donation/Sponsorship You can send via GCash : +639650332900__ <br /> __Also You can send via Paypal account: syncdevprojects@gmail.com__ <br /> Thanks and good luck! 

