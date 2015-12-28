---
Title: Test For Jeallyn's REST API reference
redirect_url: newRedicector.md
---

# Outlook Calendar REST API reference


## <a id="Swagger"> </a> Swagger


[!code-REST-i[op_build_docset](.op.build.docset.json)]


## <a id="Code_table"> </a>Code table


<!-- BEGINSECTION class="tabbedCodeSnippets" data-resources="OutlookServices.Calendar" -->
```cs-i
var outlookClient = await CreateOutlookClientAsync("Calendar");
var events = await outlookClient.Me.Events
  .Take(10)
  .ExecuteAsync();
 
foreach(var calendarEvent in events.CurrentPage)
{
  System.Diagnostics.Debug.WriteLine("Event '{0}'.", calendarEvent.Subject);
}
 
```
```javascript-i
outlookClient.me.events.getEvents().fetch().then(function (result) {
    result.currentPage.forEach(function (event) {
console.log('Event "' + event.subject + '"')
    });
}, function(error) {
    console.log(error);
});
```
``` vb-i
'Declaration
Public NotInheritable Class ForEachWithBodyFactory(Of T) _
	Implements IActivityTemplateFactory
```
``` fs-i
[<Sealed>]
type ForEachWithBodyFactory<'T> =  
    class
        interface IActivityTemplateFactory
    end
```
<!-- ENDSECTION -->


##NOTE
> [!NOTE]
> This is NOTE

The above is NOTE text

> [!WARNING]
> This is WARNING

The above is WARNING text

> [!TIP]
> This is TIP

The above is TIP text

> [!IMPORTANT]
> This is IMPORTANT

The above is IMPORTANT text

> [!CAUTION]
> This is CAUTION

The above is CAUTION text

If any question, please contact me~

## <a> </a>Responsive Table
Scenario  |Permission
------------- | ------------- |
Password Sync| <li>Replicate Directory Changes.</li>  <li>Replicate Directory Changes All.</li>
Exchange Hybrid Deployment|See [Office 365 Exchange Hybrid AAD Sync write-back attributes and permissions](https://msdn.microsoft.com/library/azure/dn757602.aspx#exchange).
Password Write-back | <li>Change Password</li><li>Reset password</li>
User, Group, and Device Write-back|Write permissions to the directory objects and attributes that you wish to 'write-back'
Single Sign-On and AD FS| Domain admin permissions in the domain in which your federated servers are located. 


<div class="tableSection"><div class="contentTableWrapper"><table responsive="true"><tbody><tr><th><p>Method</p></th><th><p>Description</p></th></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/fb7sb5f9(v=vs.100).aspx">IDiaSession::get_loadAddress</a></span></p></td><td data-th="Description"><p>Retrieves the load address for the executable file that corresponds to the symbols in this symbol store. This is the same value that was passed to the <strong>put_loadAddress</strong> method.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/339f55ts(v=vs.100).aspx">IDiaSession::put_loadAddress</a></span></p></td><td data-th="Description"><p>Sets the load address for the executable file that corresponds to the symbols in this symbol store.</p><div class="alert"><div class="mtps-table" xmlns="http://www.w3.org/1999/xhtml"><div class="mtps-row"><span class="mtps-th"><img title="Note" class="cl_IC101471" id="alert_note" alt="Note" src="https://i1.int.msdn.microsoft.com/areas/global/content/clear.gif" xmlns=""><strong>Note</strong></span></div><div class="mtps-row"><span class="mtps-cell"><span>It is important to call this method when you get an <strong>IDiaSession</strong> object and before you start using the object.</span></span></div></div></div></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/fkcc8hx6(v=vs.100).aspx">IDiaSession::get_globalScope</a></span></p></td><td data-th="Description"><p>Retrieves a reference to the global scope.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/fy22w42k(v=vs.100).aspx">IDiaSession::getEnumTables</a></span></p></td><td data-th="Description"><p>Retrieves an enumerator for all tables contained in the symbol store.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/sya9d56a(v=vs.100).aspx">IDiaSession::getSymbolsByAddr</a></span></p></td><td data-th="Description"><p>Retrieves an enumerator for all named symbols at static locations.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/x7dws85t(v=vs.100).aspx">IDiaSession::findChildren</a></span></p></td><td data-th="Description"><p>Retrieves all children of a specified parent identifier that match the name and symbol type.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/ksdet6da(v=vs.100).aspx">IDiaSession::findSymbolByAddr</a></span></p></td><td data-th="Description"><p>Retrieves a specified symbol type that contains, or is closest to, a specified address.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/06d86ea1(v=vs.100).aspx">IDiaSession::findSymbolByRVA</a></span></p></td><td data-th="Description"><p>Retrieves a specified symbol type that contains, or is closest to, a specified relative virtual address (RVA).</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/3k4y0cc3(v=vs.100).aspx">IDiaSession::findSymbolByVA</a></span></p></td><td data-th="Description"><p>Retrieves a specified symbol type that contains, or is closest to, a specified virtual address (VA).</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/57z5ybc2(v=vs.100).aspx">IDiaSession::findSymbolByToken</a></span></p></td><td data-th="Description"><p>Retrieves the symbol that contains a specified metadata token.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/x0xstdf1(v=vs.100).aspx">IDiaSession::symsAreEquiv</a></span></p></td><td data-th="Description"><p>Checks to see if two symbols are equivalent.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/wcd6kex9(v=vs.100).aspx">IDiaSession::symbolById</a></span></p></td><td data-th="Description"><p>Retrieves a symbol by its unique identifier.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/2x8wya8x(v=vs.100).aspx">IDiaSession::findSymbolByRVAEx</a></span></p></td><td data-th="Description"><p>Retrieves a specified symbol type that contains, or is closest to, a specified relative virtual address and offset.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/88h4fhbt(v=vs.100).aspx">IDiaSession::findSymbolByVAEx</a></span></p></td><td data-th="Description"><p>Retrieves a specified symbol type that contains, or is closest to, a specified virtual address and offset.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/f9eaz77a(v=vs.100).aspx">IDiaSession::findFile</a></span></p></td><td data-th="Description"><p>Retrieves a source file by compiland and name. </p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/9wx4yk06(v=vs.100).aspx">IDiaSession::findFileById</a></span></p></td><td data-th="Description"><p>Retrieves a source file by source file identifier.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/t7wkd78s(v=vs.100).aspx">IDiaSession::findLines</a></span></p></td><td data-th="Description"><p>Retrieves line numbers within a specified compiland and source file identifier.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/a3s3wk3e(v=vs.100).aspx">IDiaSession::findLinesByAddr</a></span></p></td><td data-th="Description"><p>Retrieves the lines in a specified compiland that contain a specified address.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/zkafb2f9(v=vs.100).aspx">IDiaSession::findLinesByRVA</a></span></p></td><td data-th="Description"><p>Retrieves the lines in a specified compiland that contain a specified relative virtual address.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/w117fx31(v=vs.100).aspx">IDiaSession::findLinesByVA</a></span></p></td><td data-th="Description"><p>Finds the line number information for lines contained in a specified address range.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/e14bbtcz(v=vs.100).aspx">IDiaSession::findLinesByLinenum</a></span></p></td><td data-th="Description"><p>Retrieves the lines in a specified compiland by source file and line number.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/4hzxk2f3(v=vs.100).aspx">IDiaSession::findInjectedSource</a></span></p></td><td data-th="Description"><p>Retrieves a source that has been placed into the symbol store by attribute providers or other components of the compilation process.</p></td></tr><tr><td data-th="Method"><p><span><a href="https://int.msdn.microsoft.com/en-us/library/k31f3fzf(v=vs.100).aspx">IDiaSession::getEnumDebugStreams</a></span></p></td><td data-th="Description"><p>Retrieves an enumerated sequence of debug data streams.</p></td></tr></tbody></table></div></div>
