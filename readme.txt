////////////////////////////////////////////////////////////////////
S.T.A.L.K.E.R. Anomaly 1.5.2 DLTX対応日本語化MOD
////////////////////////////////////////////////////////////////////

◆概要
S.T.A.L.K.E.R. Anomaly 1.5.2用の日本語化MODです。
スクリプトファイル等によって、
テキストレイアウトの表示崩れや語順の問題などを全面的に修正しました。
さらに、派閥名とごく一部のアイテム名を除きすべて日本語表記にしました。
フォントデータについては、
大型MODであるMISERYのものをそのままお借りしました。


◆導入手順
1. その他のMODがすでに導入されている場合は、その他のMODをすべて削除します。
2. ダウンロードしたZIPファイルを展開します。
3. gamedataフォルダをゲームフォルダに上書きコピーします。

◆その他のMODをすべて削除する方法
ゲームフォルダにあるgamedataフォルダについて、
\gamedata\configs\axr_options.ltxのみを残して、すべて削除してください。
axr_options.ltxにはゲーム設定の一部が保存されています。

◆その他のMODと併用する場合の注意点
日本語化MODを最初に導入してください。

◆1.5.2対応で1.5.1日本語化MODをベースに以下のファイルをマージ
gamedata\configs\text\eng\_game_version.xml
gamedata\configs\text\eng\st_mm_faction_select.xml
gamedata\configs\text\eng\ui_st_loadscreen.xml
gamedata\scripts\dynamic_news_helper.script
gamedata\scripts\inventory_upgrades.script
gamedata\scripts\item_weapon.script
gamedata\scripts\pda.script
gamedata\scripts\sim_squad_scripted.script
gamedata\scripts\tasks_fetch.script
gamedata\scripts\ui_inventory.script
gamedata\scripts\ui_mm_faction_select.script
gamedata\scripts\ui_options.script
gamedata\scripts\ui_workshop.script
gamedata\scripts\utils_ui.script

◆DLTX対応
DLTXのexeファイルにてマルチバイトフォント環境下の改行バグが修正された為、以下ファイルを修正
gamedata\configs\text\eng\st_items_ammo.xml
gamedata\configs\text\eng\st_items_artefacts.xml
gamedata\configs\text\eng\st_items_artefacts2.xml
gamedata\configs\text\eng\st_items_attachments.xml
gamedata\configs\text\eng\st_items_backpacks.xml
gamedata\configs\text\eng\st_items_consumable.xml
gamedata\configs\text\eng\st_items_container_aac.xml
gamedata\configs\text\eng\st_items_container_aam.xml
gamedata\configs\text\eng\st_items_container_iam.xml
gamedata\configs\text\eng\st_items_container_llmc.xml
gamedata\configs\text\eng\st_items_cooking.xml
gamedata\configs\text\eng\st_items_devices.xml
gamedata\configs\text\eng\st_items_equipment.xml
gamedata\configs\text\eng\st_items_explosive.xml
gamedata\configs\text\eng\st_items_letters.xml
gamedata\configs\text\eng\st_items_medical.xml
gamedata\configs\text\eng\st_items_money.xml
gamedata\configs\text\eng\st_items_mutant_parts.xml
gamedata\configs\text\eng\st_items_parts.xml
gamedata\configs\text\eng\st_items_patches.xml
gamedata\configs\text\eng\st_items_quest.xml
gamedata\configs\text\eng\st_items_repair.xml
gamedata\configs\text\eng\st_items_tools.xml
gamedata\configs\text\eng\st_items_trash.xml
gamedata\configs\text\eng\st_items_upgrade.xml
gamedata\configs\text\eng\st_items_weapons.xml
gamedata\configs\text\eng\st_items_weapons_addons.xml
gamedata\configs\text\eng\st_mm_faction_select.xml
gamedata\scripts\ui_item.script
gamedata\scripts\ui_mm_faction_select.script