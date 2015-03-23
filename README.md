# menu
Модуль предназначен для создания произвольного меню
# Как использовать?
Заливаем папку include в корень сайта
Для добавления меню пишем:
<?$APPLICATION->IncludeComponent("bitrix:main.include", "", array("AREA_FILE_SHOW" => "file", "PATH" => SITE_DIR."include/menu/menu.php"), false);?>
Или:
<?
$APPLICATION->IncludeFile(SITE_DIR."include/menu/menu.php", Array(), Array(
	"MODE"      => "php",                                          
	"NAME"      => "Редактирование шаблона меню",     
	));
?>
