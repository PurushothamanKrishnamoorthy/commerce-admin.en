---
title: Add custom variables
description: Learn how to create custom variables and insert them into pages, blocks, and product content.
exl-id: 8233518a-abcf-4889-b75b-4aa503c7cebb
---
# Add custom variables

To meet the specific needs of your business, you can create custom variables and insert them into [pages](../content-design/pages.md), [blocks](../content-design/blocks.md), and [email templates](email-templates.md). The list of allowed variables that appears when you click the _Insert Variable_ button includes both [predefined](variables-predefined.md) and custom variables. The list of available variables for a specific email template is determined by the data that is associated with the template. See the [Variable Reference](variables-reference.md) for a list of frequently used email templates and their associated variables.

![Custom variables](./assets/variables-custom.png){width="600" zoomable="yes"}

>[!NOTE]
>
>Only allowed predefined or custom variables can be used in email and newsletter templates.

## Step 1: Create a custom variable

1. On the _Admin_ sidebar, go to **[!UICONTROL System]** > _[!UICONTROL Other Settings]_ > **[!UICONTROL Custom Variables]**.

1. Click **[!UICONTROL Add New Variable]**.

1. Enter an identifier for **[!UICONTROL Variable Code]**, using all lowercase characters without spaces.

   If needed, you can use an underscore character or hyphen to represent a space. For example: `my_custom_variable`

1. Enter a **[!UICONTROL Variable Name]**, which is used for internal reference. For example: `My Custom Variable`

1. To enter the value that is associated with the variable, do one of the following:

   - For **[!UICONTROL Variable HTML Value]**, enter the variable value formatted with simple HTML tags. For example:
  
      `<b>This formatted content appears in place of the variable.</b>`

   - For **[!UICONTROL Variable Plain Value]**, enter the variable value as plain text without formatting. For example:

      `This unformatted content appears in place of the variable.`

   >[!TIP]
   >
   >If you need more room, drag the lower-right corner of the text box.

   ![New custom variable](./assets/variable-custom-add.png){width="600" zoomable="yes"}

1. When complete, click **[!UICONTROL Save]**.

## Step 2: Insert the custom variable in your content

Use [!DNL Page Builder] to insert a custom variable.

1. Open the page, block, category, or product where you want to add the variable to the content.

1. Expand ![Expansion selector](../assets/icon-display-expand.png) the **[!UICONTROL Content]** section.

1. Click **[!UICONTROL Edit with Page Builder]**.

1. In the left panel, click **[!UICONTROL Elements]** and do one of the following:

   - Click in an existing text area where you want to insert the variable.

   - Drag a new **[!UICONTROL Text]** object to the stage.

1. At the far right of the editor toolbar, click ( ![Insert variable](./assets/editor-btn-insert-variable.png) ) to insert a variable.

   ![[!DNL Page Builder] stage and panel](./assets/variable-custom-pagebuilder-stage.png){width="600" zoomable="yes"}

1. In the list, select the custom variable that you want to insert and click **[!UICONTROL Insert Variable]**.

   ![New custom variable](./assets/variable-custom-insert-select.png){width="600" zoomable="yes"}

   The variable identifier appears as a placeholder in the editor.

   ![[!DNL Page Builder] stage - variable placeholder](./assets/pagebuilder-variable-inserted.png){width="600" zoomable="yes"}

1. When complete, click **[!UICONTROL Save]**.
