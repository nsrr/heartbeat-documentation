## 10.3.4 Exporting Embletta Recordings

* 1. Make sure the recording that should be exported is **<u>open</u>** and labeled with the study ID.
* 2. On the **File** menu, point to **Export**, and then click **Recording**.
* 3. The Export Data Wizard is displayed. Click **Next** to continue.
* 4. Select configure the export settings manually as you go through the wizard. You can only opt to use an export profile if you have created one previously when exporting data. Click **Next**.
 
 * **Use an export profile:** If you have saved an export profile during previous export, you can elect to use it. Select the profile you want to use from the list. You will be able to modify the profile settings as you go through the wizard.
 * **Manual configuration:** Select this option if you want to configure the export settings manually.

* 6. The wizard lists all the traces in the recording. Select which traces you want to export. A check mark in front of the trace name means that the trace will be exported. Also, use the arrow buttons on the right hand side to determine in which order the traces will be exported. Selecting a trace will activate the arrow buttons. When you are finished, click **Next**.
* 7. Select the European Data format file (EDF) Click **Next**.
* 8. Choose a location where you want to export the data. Click **Next**.

 * **An existing data location:** Select this option if the data should be exported to an existing data location in the Recording Manager. From the list of existing data locations, select the location where you want to export your data. 
No data locations will be listed here unless they have been created in **Tools | Options | Data Locations.** 
 * **Other folder:** Select this option if the data should be exported to a specific folder on the computer or network. You can either enter the location path in the text field or browse to the location by clicking the **Brows+e** button.

* 9. Select the **No gain adjustment** scaling method to use when exporting. Click **Next**. 

 * **No gain adjustment:** Gain is not changed, so no scaling errors are introduced. If the data being exported falls within a very small range compared to the range expected by the file format you may get bad results.

* 10. The wizard summarizes the settings you have chosen for the export. If you want to change the settings, click the Back button. You can click the **Save as** button to save the settings as an export profile. Using an export profile will save you from having to choose the export settings each time you export data.
* 11. Click **Next** to start the export process.
* 12. Click **Finish** to close the Export Data Wizard.
* 13. Rename the Folder that the files live in with the 

 * [CR] [techID]_[date of study].

   * An example of this format would be CRtechID_10292007 for certification ( CR103_10292007)

 * [StudyID] [techID]_[date of study].

   * An example of this format would be StudyIDtechID_10292007 ( 1234103_10292007)

* 14.	Right click on the folder to create a zip file and use the same naming scheme as above and FTP to the Reading Center.


<div class="center">
<div class="btn-group">
  <a href=":pages_path:/manuals/portable-sleep-monitoring/10-03-03-01-examples.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    10.3.3.1 Examples
  </a>

  <a href=":pages_path:/manuals/portable-sleep-monitoring" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Portable Sleep Monitoring
  </a>

  <a href=":pages_path:/manuals/portable-sleep-monitoring/10-04-01-study-receipt.md" class="btn btn-success">
    10.4.1 Study Receipt
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>