# menu
������ ������������ ��� �������� ������������� ����
# ��� ������������?
�������� ����� include � ������ �����
��� ���������� ���� �����:
<?$APPLICATION->IncludeComponent("bitrix:main.include", "", array("AREA_FILE_SHOW" => "file", "PATH" => SITE_DIR."include/menu/menu.php"), false);?>
���:
<?
$APPLICATION->IncludeFile(SITE_DIR."include/menu/menu.php", Array(), Array(
	"MODE"      => "php",                                          
	"NAME"      => "�������������� ������� ����",     
	));
?>
