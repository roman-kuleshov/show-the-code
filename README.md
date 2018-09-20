# show-the-code

correlationId: "1aaaa73ab2a04e519aa1e887b52638d4"
exceptionMessage: "Attempt to fectch invalid cycle with id `30` from BillingCycles storage."
exceptionType: "ArgumentException"
message: "An error has occurred."
paramName: null
stackTrace: "   at ServiceModelEx.ServiceFabric.ChannelInvokerBase`1.InvokeEnd(Task response, IClientChannel channel)
↵   at ServiceModelEx.ServiceFabric.ChannelInvokerBase`1.<>c__DisplayClass10_0`1.<InvokeAsync>b__0(Task`1 result)
↵   at Trov.API.Controllers.Sic.AccountStatusController.<GetAccountStatusSummaryAsync>d__5.MoveNext() in C:\agent\_work\13\s\Trov.API\Controllers\Sic\AccountStatusController.cs:line 57
↵   at System.Web.Http.Controllers.ApiControllerActionInvoker.<InvokeActionAsyncCore>d__1.MoveNext()
↵   at System.Web.Http.Filters.ActionFilterAttribute.<CallOnActionExecutedAsync>d__6.MoveNext()
↵   at System.Web.Http.Filters.ActionFilterAttribute.<CallOnActionExecutedAsync>d__6.MoveNext()
↵   at System.Web.Http.Filters.ActionFilterAttribute.<ExecuteActionFilterAsyncCore>d__5.MoveNext()
↵   at System.Web.Http.Filters.ActionFilterAttribute.<CallOnActionExecutedAsync>d__6.MoveNext()
↵   at System.Web.Http.Filters.ActionFilterAttribute.<CallOnActionExecutedAsync>d__6.MoveNext()
↵   at System.Web.Http.Filters.ActionFilterAttribute.<ExecuteActionFilterAsyncCore>d__5.MoveNext()
↵   at Trov.API.Filters.EmailConfirmationAccessFilter.<ExecuteActionFilterAsync>d__9.MoveNext() in C:\agent\_work\13\s\Trov.API\Filters\EmailConfirmationAccessFilter.cs:line 48
↵   at Trov.API.Filters.EndpointAccessFilter.<ExecuteActionFilterAsync>d__4.MoveNext() in C:\agent\_work\13\s\Trov.API\Filters\EndpointAccessFilter.cs:line 32
↵   at System.Web.Http.Controllers.ActionFilterResult.<ExecuteAsync>d__5.MoveNext()
↵   at System.Web.Http.Filters.AuthorizationFilterAttribute.<ExecuteAuthorizationFilterAsyncCore>d__3.MoveNext()
↵   at System.Web.Http.Controllers.AuthenticationFilterResult.<ExecuteAsync>d__5.MoveNext()
↵   at System.Web.Http.Dispatcher.HttpControllerDispatcher.<SendAsync>d__15.MoveNext()"
