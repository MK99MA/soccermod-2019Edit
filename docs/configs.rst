.. _configs:

===================
General Information
===================

SoMoE-19 creates different config files at its first start or whenever one of those files is missing.
Overal there are 11 files that are generated and found in

	.. code-block:: none
	
		cstrike/cfg/sm_soccermod

whereas 3 of them are only used to store information and **should not be edited manually**.

Most other files can be edited manually, but only 
 - soccer_mod_GKAreas.cfg
 - soccer_mod_mapdefaults.cfg
 - soccer_mod_skins.cfg
 - soccer_mod_downloads.cfg

have to be edited by opening them with a text-editor of your choice.

Every other file is editable ingame.

----

-----------------------
List of generated files
-----------------------

| :ref:`conf-main`
| Main configuration controlling most toggles and settings.

| :ref:`conf-admins`
| Custom admin file to grant players access to certain admin features.

| :ref:`conf-maps`
| List of maps that should activate certain features of the plugin.

| :ref:`conf-pos`
| *NO CONFIG* - Storage for the selected positions of every player.

| :ref:`conf-downloads`
| *MANUAL CONFIG* - Determines which files are downloaded to the clients when joining.

| :ref:`conf-gk`
| Determines the areas around a goal needed to allow tracking of saves. Setable from within the game.

| :ref:`conf-last-match`
| *NO CONFIG* - Storage for matchlogs (if activated). Old logs will be moved to /sm_soccermod/logs.

| :ref:`conf-defaults`
| *MANUAL CONFIG* - Set default values for period and breaklength per map.

| :ref:`conf-matchlog`
| Advanced control regarding automatic matchlog generation.

| :ref:`conf-personal`
| *NO CONFIG* - Storage for personal cannon settings of every client.

| :ref:`conf-skins`
| *MANUAL CONFIG* - Add skins that are selectable ingame form a menu in here.

| :ref:`conf-replacer`
| *MANUAL CONFIG* - Add decals to be placed on maps in here.  

| :ref:`conf-shouts`
| Library of added and usable shouts on the server.

.. tip::
   Every file got its own site in this documentation. Make sure to check them out if you're having issues!
