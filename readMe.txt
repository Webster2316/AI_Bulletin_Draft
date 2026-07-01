Site Link To visulaise where each section is:
https://webster2316.github.io/Weekly_Digest_SSA/

##Template for weekly digest - INSTRUCTIONS

METHOD 1:
-Create new file and name it by the week. keep the format YYYY-MM_DD-MM_DD.html
-copy paste everything in Index.html/ from the previous week's file(To save time from having to enter all events all over) into the new file. 
Items details can easily be edited in outlook so no need to work on that.
-Based on the items for the week, copy paste/Delete the each item SECTION. 
This is to have editable fields and preserve styling. Outlook does not support copying/creating sections in its local editor.
-Delete the examples

OUTLOOK:
-copy the full code and go to outlook to send a new mail
-If not installed, add the outlook add-in: Insert Html bt Designmodo
-Opens up the add-in and paste your code
You can edit item details here

Use Ctrl+F in your editor to locate templates by their comment tags: 
event:
<!-- EVENT ITEM TEMPLATE -->
under for action:
<!-- TEMPLATE FOR REVIEW ITEM -->
<!-- TEMPLATE FOR PUBLIC COMMENTS ITEM -->
under for noting:
  <!-- TEMPLATE FOR ADVISORY ITEM -->
  <!-- TEMPLATE FOR NOTING ITEM -->

Note: Each template includes an ending comment (e.g., <!-- END OF [Type of event] ITEM -->) to clearly indicate the end of the template section. Copy all code between the template header comment and the corresponding end comment when creating a new entry.

Individual element codes to use:

  <!-- EVENT: COPY PASTE ITEM ACCORDINGLY-->
         <!-- EVENT ITEM TEMPLATE -->
            <tr>
  <td style="border-bottom:1px solid #e8e3da;padding:0;">
    <table width="100%" cellpadding="0" cellspacing="0" border="0">

      <!-- Date + Title row -->
      <tr>
      <td style="padding:14px 28px;">
        <table width="100%" cellpadding="0" cellspacing="0" border="0">
        <tr>
          <td width="52" valign="top" style="background-color:#281e7e;border-radius:3px;text-align:center;padding:6px 4px;width:52px;">
            <span style="display:block;font-family:'Yu Gothic UI',sans-serif;font-size:20px;font-weight:700;color:#ffffff;line-height:1;">day</span>
            <span style="display:block;font-family:'Yu Gothic UI',sans-serif;font-size:9px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:#f9f6ff;margin-top:3px;">month</span>
          </td>
          <td width="16">&nbsp;</td>
          <td valign="top">
            <p style="margin:0 0 3px;font-family:'Yu Gothic UI',sans-serif;font-size:15px;font-weight:700;color:#2bc4c2;line-height:1.3;">Event name</p>
            <p style="margin:0;font-family:'Yu Gothic UI',sans-serif;font-size:12px;color:#000000;letter-spacing:0.5px;">time frame</p>
          </td>
        </tr>
        </table>
      </td>
      </tr>

      <!-- Body -->
      <tr>
      <td style="padding:0 28px 16px 96px;font-family:'Yu Gothic UI',sans-serif;font-size:14px;line-height:1.7;color:#000000;border-top:1px solid #e8e3da;">
        <p style="margin:10px 0 8px;">
          <span style="display:inline-block;background:#f4f1ec;border:1px solid #e8e3da;border-radius:2px;font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#000000;padding:2px 8px;margin-right:6px;">inivited group</span>
          <span style="display:inline-block;background:#f4f1ec;border:1px solid #e8e3da;border-radius:2px;font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#000000;padding:2px 8px;">type of event</span>
        </p>
        <p style="margin:0 0 6px;"><strong>Venue:</strong> edit venue name</p>
        <p style="margin:0;">Registration: <a href="#" style="color:#81bce9;text-decoration:underline;">add registration link if applicable</a></p>
          <p style="margin:0;">Event description if applicable</p>
      </td>
      </tr>

    </table>
  </td>
  </tr>
<!-- END OF EVENT ITEM -->


 <!-- REVIEW ITEM: COPY PASTE ITEM ACCORDINGLY-->
    <!-- DELETE IF NOT NEEDED -->
  <!-- TEMPLATE FOR REVIEW ITEM -->
     <tr>
  <td style="border-bottom:1px solid #e8e3da;padding:0;">
    <table width="100%" cellpadding="0" cellspacing="0" border="0">
      <tr>
      <td style="padding:14px 28px;">
        <table width="100%" cellpadding="0" cellspacing="0" border="0">
        <tr>
          <td valign="top" style="white-space:nowrap;width:1%;padding-right:14px;">
            <span style="display:inline-block;background:#d0a523;border-radius:2px;font-family:'Yu Gothic UI',sans-serif;font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#ffffff;padding:3px 8px;">Review</span>
          </td>
          <td valign="top">
            <p style="margin:0 0 2px;font-family:'Yu Gothic UI',sans-serif;font-size:14px;font-weight:700;color:#2bc4c2;line-height:1.3;">Title</p>
            <p style="margin:0;font-family:'Yu Gothic UI',sans-serif;font-size:12px;color:#000000;"><a href="#" style="color:#81bce9;text-decoration:underline;">document link</a></p>
          </td>
        </tr>
        </table>
      </td>
      </tr>
      <tr>
       <td style="padding:0 28px 16px;font-family:'Yu Gothic UI',sans-serif;font-size:14px;line-height:1.7;color:#000000;background:#faf9f6;border-top:1px solid #e8e3da;">
        <p style="margin:10px 0 8px;">
          <span style="display:inline-block;background:#f4f1ec;border:1px solid #e8e3da;border-radius:2px;font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#000000;padding:2px 8px;margin-right:6px;">Committee 1</span>
          <span style="display:inline-block;background:#f4f1ec;border:1px solid #e8e3da;border-radius:2px;font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#000000;padding:2px 8px;">Committee 2</span>
        </p>
        <p style="margin:0 0 4px;font-family:'Yu Gothic UI',sans-serif;font-size:13px;font-weight:700;color:#000000;">Action Required</p>
        <p style="margin:0 0 14px;">action required and provide comments or feedback to <a href="mailto:anis@ssa.org.sg" style="color:#81bce9;text-decoration:none;">anis@ssa.org.sg</a>, if any.</p>
        <p style="margin:0 0 4px;font-family:'Yu Gothic UI',sans-serif;font-size:13px;font-weight:700;color:#000000;">Background</p>
        <p style="margin:0;">backgroud details</p>
      </td>
      </tr>
    </table>
  </td>
  </tr>
<!-- END OF REVIEW ITEM -->

  <!-- PUBLIC COMMENTS ITEM: COPY PASTE ITEM ACCORDINGLY-->
    <!-- DELETE IF NOT NEEDED -->
  <!-- TEMPLATE FOR PUBLIC COMMENTS ITEM -->
  <tr>
  <td style="border-bottom:1px solid #e8e3da;padding:0;">
    <table width="100%" cellpadding="0" cellspacing="0" border="0">
      <tr>
      <td style="padding:14px 28px;">
        <table width="100%" cellpadding="0" cellspacing="0" border="0">
        <tr>
          <td valign="top" style="white-space:nowrap;width:1%;padding-right:14px;">
            <span style="display:inline-block;background:#81bce9;border-radius:2px;font-family:'Yu Gothic UI',sans-serif;font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#f9f6ff;padding:3px 8px;">Public Comments</span>
          </td>
          <td valign="top">
            <p style="margin:0 0 2px;font-family:'Yu Gothic UI',sans-serif;font-size:14px;font-weight:700;color:#2bc4c2;line-height:1.3;">Item Name</p>
            <p style="margin:0;font-family:'Yu Gothic UI',sans-serif;font-size:12px;color:#000000;"><a href="https://ssaorgsg.sharepoint.com/:b:/s/SSAKnowledgeHub/IQCBNGbvSW7hS70dB0NdXWWAAfTPgaHmj7LaDJLGbvbhdck?e=5vZaZk" style="color:#81bce9;text-decoration:underline;">Main document link. Delete and add in main body if more than one</a></p>
          </td>
        </tr>
        </table>
      </td>
      </tr>
      <tr>
      <td style="padding:0 28px 16px;font-family:'Yu Gothic UI',sans-serif;font-size:14px;line-height:1.7;color:#000000;background:#faf9f6;border-top:1px solid #e8e3da;">
       <p style="margin:10px 0 8px;">
          <span style="display:inline-block;background:#f4f1ec;border:1px solid #e8e3da;border-radius:2px;font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#000000;padding:2px 8px;margin-right:6px;">Committee 1</span>
          <span style="display:inline-block;background:#f4f1ec;border:1px solid #e8e3da;border-radius:2px;font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#000000;padding:2px 8px;">Committee 2</span>
        </p>
        <p style="margin:0 0 6px;font-family:'Yu Gothic UI',sans-serif;font-size:12px;font-weight:700;color:#cc3300;">&#9888; Urgent/deadline. edit accordingly</p>
         <p style="margin:0 0 4px;font-family:'Yu Gothic UI',sans-serif;font-size:13px;font-weight:700;color:#000000;">Action Required</p>
        <p style="margin:0 0 14px;">action required and provide comments or feedback to <a href="mailto:anis@ssa.org.sg" style="color:#81bce9;text-decoration:none;">anis@ssa.org.sg</a>, if any.</p>
        <p style="margin:0 0 4px;font-family:'Yu Gothic UI',sans-serif;font-size:13px;font-weight:700;color:#000000;">Background</p>
        <p style="margin:0;">backgroud details</p>
      </td>
      </tr>
    </table>
  </td>
  </tr>
<!-- END OF PUBLIC COMMENTS ITEM -->


 <!-- ADVISORY ITEM: COPY PASTE ITEM ACCORDINGLY-->
    <!-- DELETE IF NOT NEEDED -->
  <!-- TEMPLATE FOR ADVISORY ITEM -->
  <tr>
  <td style="border-bottom:1px solid #e8e3da;padding:0;">
    <table width="100%" cellpadding="0" cellspacing="0" border="0">
      <tr>
      <td style="padding:14px 28px;">
        <table width="100%" cellpadding="0" cellspacing="0" border="0">
        <tr>
          <td valign="top" style="white-space:nowrap;width:1%;padding-right:14px;">
            <span style="display:inline-block;background:#730303;border-radius:2px;font-family:'Yu Gothic UI',sans-serif;font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#f9f6ff;padding:3px 8px;">Advisory</span>
          </td>
          <td valign="top">
            <p style="margin:0;font-family:'Yu Gothic UI',sans-serif;font-size:14px;font-weight:700;color:#2bc4c2;line-height:1.3;">Item Name</p>
          </td>
        </tr>
        </table>
      </td>
      </tr>
      <tr>
      <td style="padding:0 28px 16px;font-family:'Yu Gothic UI',sans-serif;font-size:14px;line-height:1.7;color:#000000;background:#faf9f6;border-top:1px solid #e8e3da;">

           <p style="margin:10px 0 8px;">
          <span style="display:inline-block;background:#f4f1ec;border:1px solid #e8e3da;border-radius:2px;font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#000000;padding:2px 8px;margin-right:6px;">Committee 1</span>
          <span style="display:inline-block;background:#f4f1ec;border:1px solid #e8e3da;border-radius:2px;font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#000000;padding:2px 8px;">Committee 2</span>
        </p>
      

        <p style="margin:0 0 4px;font-family:'Yu Gothic UI',sans-serif;font-size:13px;font-weight:700;color:#000000;">Action Required:</p>
        <p style="margin:0 0 6px;">ACTION TO EDIT:</p>
        <p style="margin:0 0 4px;font-family:'Yu Gothic UI',sans-serif;font-size:13px;font-weight:700;color:#000000;">Background:</p>
        <p style="margin:0 0 14px;">Background details</p>
      </td>
      </tr>
    </table>
  </td>
  </tr>
<!-- END OF ADVISORY ITEM -->


   <!-- FOR NOTING ITEM: COPY PASTE ITEM ACCORDINGLY-->
    <!-- DELETE IF NOT NEEDED -->
  <!-- TEMPLATE FOR NOTING ITEM -->
  <tr>
  <td style="border-bottom:1px solid #e8e3da;padding:0;">
    <table width="100%" cellpadding="0" cellspacing="0" border="0">
      <tr>
      <td style="padding:14px 28px;">
        <table width="100%" cellpadding="0" cellspacing="0" border="0">
        <tr>
          <td valign="top" style="white-space:nowrap;width:1%;padding-right:14px;">
            <span style="display:inline-block;background:#281e7e;border-radius:2px;font-family:'Yu Gothic UI',sans-serif;font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#f9f6ff;padding:3px 8px;">Doc src name(e.g IMO)</span>
          </td>
          <td valign="top">
            <p style="margin:0 0 2px;font-family:'Yu Gothic UI',sans-serif;font-size:14px;font-weight:700;color:#2bc4c2;line-height:1.3;">Item name</p>
            <p style="margin:0;font-family:'Yu Gothic UI',sans-serif;font-size:12px;color:#000000;"><a href="#" style="color:#81bce9;text-decoration:underline;">Document link either here</p>
          </td>
        </tr>
        </table>
      </td>
      </tr>
      <tr>
      <td style="padding:0 28px 16px;font-family:'Yu Gothic UI',sans-serif;font-size:14px;line-height:1.7;color:#000000;background:#faf9f6;border-top:1px solid #e8e3da;">
     <p style="margin:10px 0 8px;">
          <span style="display:inline-block;background:#f4f1ec;border:1px solid #e8e3da;border-radius:2px;font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#000000;padding:2px 8px;margin-right:6px;">Committee 1</span>
          <span style="display:inline-block;background:#f4f1ec;border:1px solid #e8e3da;border-radius:2px;font-size:11px;font-weight:700;letter-spacing:1px;text-transform:uppercase;color:#000000;padding:2px 8px;">Committee 2</span>
        </p>
             <p style="margin:14px 0 4px;font-family:'Yu Gothic UI',sans-serif;font-size:13px;font-weight:700;color:#000000;">Documents:</p>
        <table cellpadding="0" cellspacing="0" border="0" style="margin:0 0 14px;">
          <tr>
            <td style="width:24px;vertical-align:top;">1.</td>
            <td><a href="#" style="color:#81bce9;text-decoration:underline;">Or link here. DELETE IF NOT NEEDED</a></td>
          </tr>
        </table>

        <p style="margin:0 0 4px;font-family:'Yu Gothic UI',sans-serif;font-size:13px;font-weight:700;color:#000000;">Remarks:</p>
        <p style="margin:0 0 6px;">Remarks to edit</p>
        </td>
      </tr>
    </table>
  </td>
  </tr>
<!-- END OF NOTING ITEM -->
