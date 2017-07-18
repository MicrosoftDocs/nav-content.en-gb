<properties
                pageTitle="How to: Revalue Inventory| Dynamics NAV"
                description="Describes how to appreciate or depreciate the value of one or more items in inventory by posting their current, calculated value."
                services="project-madeira"
                documentationCenter=""
                authors="SorenGP"
/>
<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="11/07/2016"
    ms.author="SorenGP" />


# <a name="how-to-revalue-inventory"></a>How to: Revalue Inventory   
If you want to appreciate or depreciate an item or a specific item ledger entry, you must use the revaluation journal.

## <a name="to-revalue-inventory"></a>To revalue inventory
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Revaluation Journal**, and then choose the related link.
2. Choose the **Calculate Inventory Value** action.
3. In the **Calculate Inventory Value** window, fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.
4. Choose the **OK** button.
5. On each line in the **Revaluation Journal** window, in the **Unit Cost (Revalued)** field, enter the new unit cost. Alternatively, enter the new total amount in the **Inventory Value (Revalued)** field.

    The relevant fields are automatically updated. Note that the **Amount** field shows the actual change in inventory value for the selected item ledger entry. It calculates the difference between the **Inventory Value (Calculated)** field and the **Inventory Value (Revalued)** field.

6. When you have completed all lines in the revaluation journal, choose the **Post** action.

New value entries are now created to reflect the revaluations that you have posted. You can see the new values on the respective item cards.

## <a name="see-also"></a>See Also
[Manage Inventory](inventory-manage-inventory.md)  
[Manage Sales](sales-manage-sales.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)  
[Work With Dynamics NAV](ui-work-product.md)

