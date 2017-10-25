---
title: Using the Dynamics NAV Content Pack for Power BI
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: ad9519b8ce9c244480308ccc99c05e78e4926b06
ms.contentlocale: en-ca
ms.lasthandoff: 10/16/2017

---

# <a name="using-the-dynamics-nav-content-pack-for-power-bi"></a><span data-ttu-id="49efc-102">Using the Dynamics NAV Content Pack for Power BI</span><span class="sxs-lookup"><span data-stu-id="49efc-102">Using the Dynamics NAV Content Pack for Power BI</span></span>
<span data-ttu-id="49efc-103">Getting insights into your Dynamics NAV data is easy with Power BI and the Dynamics NAV content pack.</span><span class="sxs-lookup"><span data-stu-id="49efc-103">Getting insights into your Dynamics NAV data is easy with Power BI and the Dynamics NAV content pack.</span></span> <span data-ttu-id="49efc-104">Power BI retrieves your data and then builds an out-of-the-box dashboard and reports based on that data.</span><span class="sxs-lookup"><span data-stu-id="49efc-104">Power BI retrieves your data and then builds an out-of-the-box dashboard and reports based on that data.</span></span>  

<span data-ttu-id="49efc-105">The content pack is preconfigured to work with sales data and financial data from the demonstration company that you get when you sign up for the Dynamics NAV preview.</span><span class="sxs-lookup"><span data-stu-id="49efc-105">The content pack is preconfigured to work with sales data and financial data from the demonstration company that you get when you sign up for the Dynamics NAV preview.</span></span>  

- <span data-ttu-id="49efc-106">Choose any visual on the dashboard to bring up one of seven underlying reports.</span><span class="sxs-lookup"><span data-stu-id="49efc-106">Choose any visual on the dashboard to bring up one of seven underlying reports.</span></span>  
- <span data-ttu-id="49efc-107">Filter the report or add fields that you want to monitor.</span><span class="sxs-lookup"><span data-stu-id="49efc-107">Filter the report or add fields that you want to monitor.</span></span>  
- <span data-ttu-id="49efc-108">Pin this customized view to the dashboard to continue tracking.</span><span class="sxs-lookup"><span data-stu-id="49efc-108">Pin this customized view to the dashboard to continue tracking.</span></span>  
<span data-ttu-id="49efc-109">The dashboard and underlying reports refresh daily.</span><span class="sxs-lookup"><span data-stu-id="49efc-109">The dashboard and underlying reports refresh daily.</span></span> <span data-ttu-id="49efc-110">You can control the refresh schedule and modify the frequency on the dataset.</span><span class="sxs-lookup"><span data-stu-id="49efc-110">You can control the refresh schedule and modify the frequency on the dataset.</span></span>  

## <a name="accessing-dynamics-nav-in-power-bi"></a><span data-ttu-id="49efc-111">Accessing Dynamics NAV in Power BI</span><span class="sxs-lookup"><span data-stu-id="49efc-111">Accessing Dynamics NAV in Power BI</span></span>
<span data-ttu-id="49efc-112">To see your Dynamics NAV data in Power BI, you must have the following:</span><span class="sxs-lookup"><span data-stu-id="49efc-112">To see your Dynamics NAV data in Power BI, you must have the following:</span></span>  

- <span data-ttu-id="49efc-113">Access to Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="49efc-113">Access to Dynamics NAV.</span></span> <span data-ttu-id="49efc-114">For more information, see [Dynamics NAV](http://go.microsoft.com/fwlink/?LinkID=759714).</span><span class="sxs-lookup"><span data-stu-id="49efc-114">For more information, see [Dynamics NAV](http://go.microsoft.com/fwlink/?LinkID=759714).</span></span>  
- <span data-ttu-id="49efc-115">Access to Power BI.</span><span class="sxs-lookup"><span data-stu-id="49efc-115">Access to Power BI.</span></span> <span data-ttu-id="49efc-116">For more information, see [Power BI](https://powerbi.microsoft.com).</span><span class="sxs-lookup"><span data-stu-id="49efc-116">For more information, see [Power BI](https://powerbi.microsoft.com).</span></span>

<span data-ttu-id="49efc-117">On the Power BI site, you can find additional information about [adding the Dynamics NAV content pack to Power BI](http://go.microsoft.com/fwlink/?LinkID=760850).</span><span class="sxs-lookup"><span data-stu-id="49efc-117">On the Power BI site, you can find additional information about [adding the Dynamics NAV content pack to Power BI](http://go.microsoft.com/fwlink/?LinkID=760850).</span></span>  

<span data-ttu-id="49efc-118">To access the Dynamics NAV content pack in Power BI, in the connection window, you must specify the following information:</span><span class="sxs-lookup"><span data-stu-id="49efc-118">To access the Dynamics NAV content pack in Power BI, in the connection window, you must specify the following information:</span></span>

| <span data-ttu-id="49efc-119">Field</span><span class="sxs-lookup"><span data-stu-id="49efc-119">Field</span></span>       | <span data-ttu-id="49efc-120">Description</span><span class="sxs-lookup"><span data-stu-id="49efc-120">Description</span></span>              |
|-------------|--------------------------|
|<span data-ttu-id="49efc-121">**OData Feed URL**</span><span class="sxs-lookup"><span data-stu-id="49efc-121">**OData Feed URL**</span></span>|<span data-ttu-id="49efc-122">The OData URL so Power BI can access data from your company, such as https://mybusiness.com:7048/MS/OData/Company('CRONUS%20US').</span><span class="sxs-lookup"><span data-stu-id="49efc-122">The OData URL so Power BI can access data from your company, such as https://mybusiness.com:7048/MS/OData/Company('CRONUS%20US').</span></span>|
|<span data-ttu-id="49efc-123">**Authentication method**</span><span class="sxs-lookup"><span data-stu-id="49efc-123">**Authentication method**</span></span>|<span data-ttu-id="49efc-124">Choose **Basic**.</span><span class="sxs-lookup"><span data-stu-id="49efc-124">Choose **Basic**.</span></span>|
|<span data-ttu-id="49efc-125">**User name**</span><span class="sxs-lookup"><span data-stu-id="49efc-125">**User name**</span></span>|<span data-ttu-id="49efc-126">The email account that you used to sign up for Dynamics NAV, such as *me@mybusiness.com*.</span><span class="sxs-lookup"><span data-stu-id="49efc-126">The email account that you used to sign up for Dynamics NAV, such as *me@mybusiness.com*.</span></span>|
|<span data-ttu-id="49efc-127">**Password**</span><span class="sxs-lookup"><span data-stu-id="49efc-127">**Password**</span></span>|<span data-ttu-id="49efc-128">This is the web service access key for your user account in Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="49efc-128">This is the web service access key for your user account in Dynamics NAV.</span></span>|

<span data-ttu-id="49efc-129">This means that you must get two pieces of information from Dynamics NAV: The OData URL and the web service access key for your user account.</span><span class="sxs-lookup"><span data-stu-id="49efc-129">This means that you must get two pieces of information from Dynamics NAV: The OData URL and the web service access key for your user account.</span></span>  
<span data-ttu-id="49efc-130">**Getting the URL**</span><span class="sxs-lookup"><span data-stu-id="49efc-130">**Getting the URL**</span></span>  
<span data-ttu-id="49efc-131">When you add Dynamics NAV to Power BI, you must specify a URL so Power BI can access data from your company.</span><span class="sxs-lookup"><span data-stu-id="49efc-131">When you add Dynamics NAV to Power BI, you must specify a URL so Power BI can access data from your company.</span></span> <span data-ttu-id="49efc-132">In the connection window, the URL is referred to as the **OData Feed URL**, and it must have the following format:</span><span class="sxs-lookup"><span data-stu-id="49efc-132">In the connection window, the URL is referred to as the **OData Feed URL**, and it must have the following format:</span></span>

         https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
<span data-ttu-id="49efc-133">In this example, *mybusiness* is the name of your Dynamics NAV service, and *CRONUS US* is the name of the demonstration company with *%20* representing the space in the name.</span><span class="sxs-lookup"><span data-stu-id="49efc-133">In this example, *mybusiness* is the name of your Dynamics NAV service, and *CRONUS US* is the name of the demonstration company with *%20* representing the space in the name.</span></span>   
<span data-ttu-id="49efc-134">To get the URL, in Dynamics NAV, search for and open the **Web Services** window.</span><span class="sxs-lookup"><span data-stu-id="49efc-134">To get the URL, in Dynamics NAV, search for and open the **Web Services** window.</span></span> <span data-ttu-id="49efc-135">This window lists the web services that are currently available, and you can copy the link from the **OData URL** field for one of the default OData web services.</span><span class="sxs-lookup"><span data-stu-id="49efc-135">This window lists the web services that are currently available, and you can copy the link from the **OData URL** field for one of the default OData web services.</span></span>  
<span data-ttu-id="49efc-136">**Getting the web service access key**</span><span class="sxs-lookup"><span data-stu-id="49efc-136">**Getting the web service access key**</span></span>  
<span data-ttu-id="49efc-137">In order to use data from Dynamics NAV, in Power BI, in the **Connect to Dynamics NAV** window, you must specify your user name, which is your email account, and a password.</span><span class="sxs-lookup"><span data-stu-id="49efc-137">In order to use data from Dynamics NAV, in Power BI, in the **Connect to Dynamics NAV** window, you must specify your user name, which is your email account, and a password.</span></span> <span data-ttu-id="49efc-138">The password is the web service access key that is set up for your user account in Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="49efc-138">The password is the web service access key that is set up for your user account in Dynamics NAV.</span></span>  
<span data-ttu-id="49efc-139">To get a web service access key, in Dynamics NAV, search for the **Users** window, and then open the card for your user account.</span><span class="sxs-lookup"><span data-stu-id="49efc-139">To get a web service access key, in Dynamics NAV, search for the **Users** window, and then open the card for your user account.</span></span> <span data-ttu-id="49efc-140">On the **Web Service Access** FastTab, copy the contents of the **Web Service Access Key** field.</span><span class="sxs-lookup"><span data-stu-id="49efc-140">On the **Web Service Access** FastTab, copy the contents of the **Web Service Access Key** field.</span></span> <span data-ttu-id="49efc-141">If the field is blank, in the ribbon, choose **Change Web Service Access Key**, choose the **Key Never Expires** field, and then choose the OK button.</span><span class="sxs-lookup"><span data-stu-id="49efc-141">If the field is blank, in the ribbon, choose **Change Web Service Access Key**, choose the **Key Never Expires** field, and then choose the OK button.</span></span> <span data-ttu-id="49efc-142">You can then copy the key.</span><span class="sxs-lookup"><span data-stu-id="49efc-142">You can then copy the key.</span></span>  

## <a name="getting-data-from-dynamics-nav"></a><span data-ttu-id="49efc-143">Getting Data from Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="49efc-143">Getting Data from Dynamics NAV</span></span>
<span data-ttu-id="49efc-144">The Dynamics NAV dashboard shows the most typical reports that you will want to use to track your business.</span><span class="sxs-lookup"><span data-stu-id="49efc-144">The Dynamics NAV dashboard shows the most typical reports that you will want to use to track your business.</span></span> <span data-ttu-id="49efc-145">The data is extracted from your Dynamics NAV company using web services to read live data.</span><span class="sxs-lookup"><span data-stu-id="49efc-145">The data is extracted from your Dynamics NAV company using web services to read live data.</span></span> <span data-ttu-id="49efc-146">In Dynamics NAV, the **Web Services** window lists the web services that have been set up for you, including the following that are consumed by the content pack in Power BI:</span><span class="sxs-lookup"><span data-stu-id="49efc-146">In Dynamics NAV, the **Web Services** window lists the web services that have been set up for you, including the following that are consumed by the content pack in Power BI:</span></span>  

- <span data-ttu-id="49efc-147">ItemSalesAndProfit</span><span class="sxs-lookup"><span data-stu-id="49efc-147">ItemSalesAndProfit</span></span>  
- <span data-ttu-id="49efc-148">ItemSalesByCustomer</span><span class="sxs-lookup"><span data-stu-id="49efc-148">ItemSalesByCustomer</span></span>  
- <span data-ttu-id="49efc-149">powerbifinance-setup</span><span class="sxs-lookup"><span data-stu-id="49efc-149">powerbifinance-setup</span></span>  
- <span data-ttu-id="49efc-150">SalesDashboard</span><span class="sxs-lookup"><span data-stu-id="49efc-150">SalesDashboard</span></span>  
- <span data-ttu-id="49efc-151">SalesOpportunities</span><span class="sxs-lookup"><span data-stu-id="49efc-151">SalesOpportunities</span></span>  
- <span data-ttu-id="49efc-152">SalesOrdersBySalesPerson</span><span class="sxs-lookup"><span data-stu-id="49efc-152">SalesOrdersBySalesPerson</span></span>  
- <span data-ttu-id="49efc-153">TopCustomerOverview</span><span class="sxs-lookup"><span data-stu-id="49efc-153">TopCustomerOverview</span></span>  

<span data-ttu-id="49efc-154">**Note**: If you change the name of any of these web services, the data will not show up in Power BI.</span><span class="sxs-lookup"><span data-stu-id="49efc-154">**Note**: If you change the name of any of these web services, the data will not show up in Power BI.</span></span>  
<span data-ttu-id="49efc-155">If you want to add use other data in Power BI, you must find the tables in Dynamics NAV, expose them as web services, and then add them to the content pack.</span><span class="sxs-lookup"><span data-stu-id="49efc-155">If you want to add use other data in Power BI, you must find the tables in Dynamics NAV, expose them as web services, and then add them to the content pack.</span></span> <span data-ttu-id="49efc-156">This is an advanced scenario, and we recommend that you start with the data that is already available in Power BI.</span><span class="sxs-lookup"><span data-stu-id="49efc-156">This is an advanced scenario, and we recommend that you start with the data that is already available in Power BI.</span></span>  

## <a name="troubleshooting"></a><span data-ttu-id="49efc-157">Troubleshooting</span><span class="sxs-lookup"><span data-stu-id="49efc-157">Troubleshooting</span></span>
<span data-ttu-id="49efc-158">The Power BI dashboard relies on the published web services that are listed above, and it will show data from the demonstration company or your own company if you import data from your current finance-setup solution.</span><span class="sxs-lookup"><span data-stu-id="49efc-158">The Power BI dashboard relies on the published web services that are listed above, and it will show data from the demonstration company or your own company if you import data from your current finance-setup solution.</span></span> <span data-ttu-id="49efc-159">However, if something goes wrong, this section provides a workaround for the most typical issues.</span><span class="sxs-lookup"><span data-stu-id="49efc-159">However, if something goes wrong, this section provides a workaround for the most typical issues.</span></span>  

<span data-ttu-id="49efc-160">**"Parameter validation failed, please make sure all parameters are valid"**</span><span class="sxs-lookup"><span data-stu-id="49efc-160">**"Parameter validation failed, please make sure all parameters are valid"**</span></span>  
<span data-ttu-id="49efc-161">If you see this error after you enter your Dynamics NAV URL, make sure the following requirements are satisfied:</span><span class="sxs-lookup"><span data-stu-id="49efc-161">If you see this error after you enter your Dynamics NAV URL, make sure the following requirements are satisfied:</span></span>  

- <span data-ttu-id="49efc-162">The URL follows exactly this pattern:</span><span class="sxs-lookup"><span data-stu-id="49efc-162">The URL follows exactly this pattern:</span></span>

    <span data-ttu-id="49efc-163">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')</span><span class="sxs-lookup"><span data-stu-id="49efc-163">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')</span></span>  
- <span data-ttu-id="49efc-164">Delete any text after the company name in parenthesis</span><span class="sxs-lookup"><span data-stu-id="49efc-164">Delete any text after the company name in parenthesis</span></span>  
- <span data-ttu-id="49efc-165">Make sure there are no trailing forward slash at the end of the URL.</span><span class="sxs-lookup"><span data-stu-id="49efc-165">Make sure there are no trailing forward slash at the end of the URL.</span></span>  
- <span data-ttu-id="49efc-166">Make sure that it is a secure connection as indicated by the URL starting with *https*.</span><span class="sxs-lookup"><span data-stu-id="49efc-166">Make sure that it is a secure connection as indicated by the URL starting with *https*.</span></span>  


<span data-ttu-id="49efc-167">**"Login failed"**</span><span class="sxs-lookup"><span data-stu-id="49efc-167">**"Login failed"**</span></span>  
<span data-ttu-id="49efc-168">If you get a "login failed" error when you log in to the dashboard, using your Dynamics NAV credentials, then this can be caused by one of the following issues:</span><span class="sxs-lookup"><span data-stu-id="49efc-168">If you get a "login failed" error when you log in to the dashboard, using your Dynamics NAV credentials, then this can be caused by one of the following issues:</span></span>

* <span data-ttu-id="49efc-169">The account you are using does not have permissions to read the Dynamics NAV data from your account.</span><span class="sxs-lookup"><span data-stu-id="49efc-169">The account you are using does not have permissions to read the Dynamics NAV data from your account.</span></span>

    <span data-ttu-id="49efc-170">Verify your user account in Dynamics NAV, and make sure that you have used the right web service access key as the password, and then try again.</span><span class="sxs-lookup"><span data-stu-id="49efc-170">Verify your user account in Dynamics NAV, and make sure that you have used the right web service access key as the password, and then try again.</span></span>  
* <span data-ttu-id="49efc-171">The Dynamics NAV  instance that you are trying to connect to does not have a valid SSL certificate.</span><span class="sxs-lookup"><span data-stu-id="49efc-171">The Dynamics NAV  instance that you are trying to connect to does not have a valid SSL certificate.</span></span> <span data-ttu-id="49efc-172">In this case you'll see a more detailed error message ("unable to establish trusted SSL relationship").</span><span class="sxs-lookup"><span data-stu-id="49efc-172">In this case you'll see a more detailed error message ("unable to establish trusted SSL relationship").</span></span>

    <span data-ttu-id="49efc-173">**Note**: Self-signed certificates are not supported.</span><span class="sxs-lookup"><span data-stu-id="49efc-173">**Note**: Self-signed certificates are not supported.</span></span>  


<span data-ttu-id="49efc-174">**"Oops"**</span><span class="sxs-lookup"><span data-stu-id="49efc-174">**"Oops"**</span></span>  
<span data-ttu-id="49efc-175">If you see an "Oops" error dialogue after you pass the authentication dialogue, this is most frequently caused by a problem connecting to the data for the content pack.</span><span class="sxs-lookup"><span data-stu-id="49efc-175">If you see an "Oops" error dialog after you pass the authentication dialog, this is most frequently caused by a problem connecting to the data for the content pack.</span></span>

* <span data-ttu-id="49efc-176">Verify that the URL follows the pattern that was specified earlier:</span><span class="sxs-lookup"><span data-stu-id="49efc-176">Verify that the URL follows the pattern that was specified earlier:</span></span>

    <span data-ttu-id="49efc-177">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')</span><span class="sxs-lookup"><span data-stu-id="49efc-177">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')</span></span>  
* <span data-ttu-id="49efc-178">A common mistake is to specify the full URL for a specific web service:</span><span class="sxs-lookup"><span data-stu-id="49efc-178">A common mistake is to specify the full URL for a specific web service:</span></span>

    <span data-ttu-id="49efc-179">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')/powerbifinance-setup</span><span class="sxs-lookup"><span data-stu-id="49efc-179">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')/powerbifinance-setup</span></span>  
* <span data-ttu-id="49efc-180">Or you might have forgotten to specify the company name:</span><span class="sxs-lookup"><span data-stu-id="49efc-180">Or you might have forgotten to specify the company name:</span></span>

    <span data-ttu-id="49efc-181">https://mybusiness.projectmadeira.com:7048/MS/OData/</span><span class="sxs-lookup"><span data-stu-id="49efc-181">https://mybusiness.projectmadeira.com:7048/MS/OData/</span></span>  


## <a name="see-also"></a><span data-ttu-id="49efc-182">See Also</span><span class="sxs-lookup"><span data-stu-id="49efc-182">See Also</span></span>
[<span data-ttu-id="49efc-183">Welcome to Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="49efc-183">Welcome to Dynamics NAV</span></span>](across-get-started.md)  

