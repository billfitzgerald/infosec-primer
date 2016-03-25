# D. Preparing Firefox for Testing

To prepare to test using Firefox, we need to clear any stored usage data that could potentially affect the results we see when we test. These preparatory steps include clearing the browser cache, all cookies, and all Web history. 

## <a name="h.browser-homepage"></a>D1 Set Firefox Home Page

To start, we will make sure that we are not logged in to Sync and that our home page is set to a blank page. To access the home page setting, click the menu icon in the top-right corner of the Firefox window.

If you are logged out of Sync, you will see this reflected in the message in the "Options" box.

<div align="center">
<figure>
<img alt="Sync options" src="images/image114.png" style="width: 198px; height: 362px;" title="Sync options">
  <br>
<figcaption>Image Caption: Sync options</figcaption>
</figure>
</div></p>

Click the **Preferences** icon to set your home page. When you are at the home page, set the home page to open to a blank page.

<div align="center">
<figure>
  <img alt="Preferences options" src="images/image39.png" width="624" height="347" title="Preferences options">
    <br>
  <figcaption>Image Caption: Preferences options</figcaption>
</figure>
</div>

By setting your browser to open to a blank page, you ensure that no extraneous cookies or trackers get set accidentally when you open your browser to start testing.

## <a name="h.browser-history"></a>D2 Clear History

In the Firefox menu, select **History** --> **Clear recent history**. A pop-up menu appears. Select **Everything** for the time range, tick all the boxes, and click **Clear Now**.

<div align="center">
<figure>
  <img alt="Clear Recent History" src="images/image42.png" width="310" height="389" title="Clear Recent History">
    <br>
  <figcaption>Image Caption: Clear recent history.</figcaption>
</figure>
</div>

## <a name="h.browser-cookies"></a>D3 Verify That Cookies Are Allowed and Do Not Track Is Off

During testing, we want to make sure that we accept all cookies and that we are not setting **Do Not Track**. 

**Note**: During regular browsing, we recommend being more selective about the cookies we accept and setting Do Not Track. While many vendors do not respect Do Not Track, it offers a degree of protection.

However, to prepare our browser for testing, enter "about:preferences#privacy" as the URL. 

<div align="center">
<figure>
  <img alt="" src="images/image115.png" width="997" height="456" title="">
    <br>
  <figcaption>Image Caption: For testing, deselect "Do Not Track," and allow all cookies.</figcaption>
</figure>
</div>

With our browser set to open to a blank page, old cookies and browsing data removed, and permissions adjusted to allow cookies, we are now set to test.

Additionally, if you are running any adblockers or plug-ins that require HTTPS (examples include HTTPS Everywhere and Privacy Badger), you should disable them on your browser prior to testing. While using extensions like this is recommended for safe browsing, they could limit the range of what we encounter while testing.

* Proceed to the next chapter: E. [Testing Scenarios and Procedures](testing_scenarios.md)
