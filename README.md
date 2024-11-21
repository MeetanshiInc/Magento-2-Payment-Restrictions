# **Magento 2 Payment Restrictions**

The **Magento 2 Payment Restrictions extension** by Meetanshi allows merchants to restrict payment methods based on specific conditions, ensuring smooth payment processing and improving customer satisfaction. This functionality helps businesses tailor the payment process to meet operational needs and comply with legal or logistical requirements.

## **How It Works**

The extension offers flexibility in configuring payment methods by enabling restrictions based on conditions such as customer groups, shipping methods, store views, and more. This ensures that customers see only the payment options relevant to them, simplifying the checkout process and enhancing user experience.

## **Key Features**

* **Rule Management:** Easily name, enable, or disable rules through the general settings.  
* **Flexible Payment Method Selection:** Choose single or multiple payment methods to restrict.  
* **Targeted Restrictions:** Apply restrictions based on customer groups, store views, or even admin users.  
* **Advanced Conditions:** Set single or multiple conditions, with the flexibility to apply rules when any or all conditions are met.  
* **Time-Based Restrictions:** Restrict payment methods based on specific times or days of the week.

## **Restrict Payment Methods by Shipping Methods**

The extension allows restricting specific payment methods for certain shipping methods to streamline operations. For instance:

## **Restrict Payment Methods by Customer Groups**

Manage payment options for different groups \- let business customers use credit cards exclusively while limiting guest payment methods for better security.

## **Restrict Payment Methods by Store View**

Tailor payment options for each store location \- show region-appropriate payment methods and remove irrelevant ones based on local preferences and market needs.

## **Advanced Conditions for Flexibility**

Set precise payment options using different factors \- from specific product categories and SKUs to order details like cart total and weight.

## **Extension Installation**

To install the **Magento 2 Payment Restrictions** extension:

### **Step 1:** 

Extract the zip folder and upload our extension to the root of your Magento 2 directory via FTP.

### **Step 2:** 

### Login to your SSH and run below commands step by step:

* php bin/magento setup:upgrade  
* For Magento version 2.0.x to 2.1.x \- php bin/magento setup:static-content:deploy  
* For Magento version 2.2.x & above \- php bin/magento setup:static-content:deploy –f  
* php bin/magento cache:flush

## **How to Configure Magento 2 Payment Restrictions Extension**

To create a new payment restriction rule in Magento 2:

### **Step 1:  Adding a New Rule**

You will find the following settings to configure the rule:

![Adding a New Rule](https://github.com/user-attachments/assets/751ed58e-8c5d-49f9-b0c6-e96654240188)

* **Rule Name:** Assign a descriptive name to the rule for easy identification.  
* **Status:** Enable or disable the rule using the dropdown menu.  
* **Payment Methods:** Select the payment methods to restrict when the specified conditions are met.  
* **Customer Groups:** Choose the customer groups for which the payment method will be restricted.  
* **Store:** Specify the store views where the payment restriction will apply.  
* **For Admin:** Set to YES if you want the payment restriction to apply in the backend as well.

### **Step 2: Setting Payment Restriction Conditions**

![Setting Payment Restriction Conditions](https://github.com/user-attachments/assets/92dd5fd4-e88f-4e6f-ae97-32bd3dd6db4e)

The extension allows you to configure payment restriction conditions based on various factors such as product attributes, cart attributes, shipping details, and customer information. Under the Conditions tab, simply choose the desired attributes and define the conditions for restricting payment methods.

### **Step 3: Days & Time-Based Restrictions**

The extension enables you to set payment restrictions based on specific days of the week and times of day. To configure this, go to the Days & Time tab and define the desired restrictions.

![Days   Time-Based Restrictions](https://github.com/user-attachments/assets/1b4cb140-6c1f-4e2d-ab8f-7f6398d72609)

After defining and enabling the payment restriction rules, the extension will apply the restrictions to payment methods on the frontend, based on the specified conditions.

## Download our [Magento 2 Payment Restrictions](https://meetanshi.com/magento-2-payment-restrictions.html) Extension
