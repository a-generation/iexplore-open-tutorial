# Tutorial on Opening Internet Explorer with PowerShell

In this tutorial, we will cover how to open Internet Explorer using PowerShell.

## Step 1: Open PowerShell

1. Press `Win + X` on your keyboard.
2. Select `Windows PowerShell` or `Windows PowerShell (Admin)` from the menu.

## Step 2: Launch Internet Explorer

Type the following command in the PowerShell console:

```powershell
(New-Object -ComObject InternetExplorer.Application).Visible = $true
