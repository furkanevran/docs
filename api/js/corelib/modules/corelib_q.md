[@serenity-is](../README.md) / [Modules](../modules.md) / corelib/q

# Module: corelib/q

This is the main entry point for `@serenity-is/corelib/q` module. This module mainly contains 
helper functions.

The types from this module are available by importing from "@serenity-is/corelib/q":

```ts
import { htmlEncode, notifyInfo } from "serenity-is/corelib/q"
notifyInfo(htmlEncode("&'<>"));
```
  
> When using classic namespaces instead of the ESM modules, the types and functions in this module are directly available from the global `Q` namespace.
> e.g. `Q.htmlEncode("&'<>")`

## Table of contents

### Namespaces

- [Authorization](corelib_q.Authorization.md)
- [Criteria](corelib_q.Criteria.md)
- [Enum](corelib_q.Enum.md)
- [ErrorHandling](corelib_q.ErrorHandling.md)
- [LayoutTimer](corelib_q.LayoutTimer.md)
- [Router](corelib_q.Router.md)
- [ScriptData](corelib_q.ScriptData.md)

### Enumerations

- [ColumnSelection](../enums/corelib_q.ColumnSelection.md)
- [CriteriaOperator](../enums/corelib_q.CriteriaOperator.md)
- [MemberType](../enums/corelib_q.MemberType.md)
- [RetrieveColumnSelection](../enums/corelib_q.RetrieveColumnSelection.md)
- [SummaryType](../enums/corelib_q.SummaryType.md)

### Classes

- [ArgumentNullException](../classes/corelib_q.ArgumentNullException.md)
- [CriteriaBuilder](../classes/corelib_q.CriteriaBuilder.md)
- [EditorAttribute](../classes/corelib_q.EditorAttribute.md)
- [Exception](../classes/corelib_q.Exception.md)
- [ISlickFormatter](../classes/corelib_q.ISlickFormatter.md)
- [InvalidCastException](../classes/corelib_q.InvalidCastException.md)
- [LT](../classes/corelib_q.LT.md)
- [Lookup](../classes/corelib_q.Lookup.md)
- [Toastr](../classes/corelib_q.Toastr.md)

### Interfaces

- [AlertOptions](../interfaces/corelib_q.AlertOptions.md)
- [CommonDialogOptions](../interfaces/corelib_q.CommonDialogOptions.md)
- [ConfirmOptions](../interfaces/corelib_q.ConfirmOptions.md)
- [DateFormat](../interfaces/corelib_q.DateFormat.md)
- [DebouncedFunction](../interfaces/corelib_q.DebouncedFunction.md)
- [DeleteRequest](../interfaces/corelib_q.DeleteRequest.md)
- [DeleteResponse](../interfaces/corelib_q.DeleteResponse.md)
- [DialogButton](../interfaces/corelib_q.DialogButton.md)
- [HandleRouteEventArgs](../interfaces/corelib_q.HandleRouteEventArgs.md)
- [IFrameDialogOptions](../interfaces/corelib_q.IFrameDialogOptions.md)
- [JQBlockUIOptions](../interfaces/corelib_q.JQBlockUIOptions.md)
- [ListRequest](../interfaces/corelib_q.ListRequest.md)
- [ListResponse](../interfaces/corelib_q.ListResponse.md)
- [Locale](../interfaces/corelib_q.Locale.md)
- [LookupOptions](../interfaces/corelib_q.LookupOptions.md)
- [NumberFormat](../interfaces/corelib_q.NumberFormat.md)
- [PostToServiceOptions](../interfaces/corelib_q.PostToServiceOptions.md)
- [PostToUrlOptions](../interfaces/corelib_q.PostToUrlOptions.md)
- [PropertyItem](../interfaces/corelib_q.PropertyItem.md)
- [PropertyItemsData](../interfaces/corelib_q.PropertyItemsData.md)
- [RetrieveLocalizationRequest](../interfaces/corelib_q.RetrieveLocalizationRequest.md)
- [RetrieveLocalizationResponse](../interfaces/corelib_q.RetrieveLocalizationResponse.md)
- [RetrieveRequest](../interfaces/corelib_q.RetrieveRequest.md)
- [RetrieveResponse](../interfaces/corelib_q.RetrieveResponse.md)
- [SaveRequest](../interfaces/corelib_q.SaveRequest.md)
- [SaveRequestWithAttachment](../interfaces/corelib_q.SaveRequestWithAttachment.md)
- [SaveResponse](../interfaces/corelib_q.SaveResponse.md)
- [SaveWithLocalizationRequest](../interfaces/corelib_q.SaveWithLocalizationRequest.md)
- [ServiceError](../interfaces/corelib_q.ServiceError.md)
- [ServiceOptions](../interfaces/corelib_q.ServiceOptions.md)
- [ServiceRequest](../interfaces/corelib_q.ServiceRequest.md)
- [ServiceResponse](../interfaces/corelib_q.ServiceResponse.md)
- [TypeMember](../interfaces/corelib_q.TypeMember.md)
- [UndeleteRequest](../interfaces/corelib_q.UndeleteRequest.md)
- [UndeleteResponse](../interfaces/corelib_q.UndeleteResponse.md)
- [UserDefinition](../interfaces/corelib_q.UserDefinition.md)

### Type Aliases

- [Dictionary](corelib_q.md#dictionary)
- [GroupByElement](corelib_q.md#groupbyelement)
- [GroupByResult](corelib_q.md#groupbyresult)
- [Grouping](corelib_q.md#grouping)
- [NotifyMap](corelib_q.md#notifymap)
- [ToastContainerOptions](corelib_q.md#toastcontaineroptions)
- [ToastrOptions](corelib_q.md#toastroptions)
- [Type](corelib_q.md#type)

### Variables

- [Config](corelib_q.md#config)
- [Culture](corelib_q.md#culture)
- [Invariant](corelib_q.md#invariant)
- [defaultNotifyOptions](corelib_q.md#defaultnotifyoptions)

### Functions

- [Criteria](corelib_q.md#criteria)
- [addAttribute](corelib_q.md#addattribute)
- [addEmptyOption](corelib_q.md#addemptyoption)
- [addOption](corelib_q.md#addoption)
- [addTypeMember](corelib_q.md#addtypemember)
- [addValidationRule](corelib_q.md#addvalidationrule)
- [alert](corelib_q.md#alert)
- [alertDialog](corelib_q.md#alertdialog)
- [any](corelib_q.md#any)
- [attrEncode](corelib_q.md#attrencode)
- [baseValidateOptions](corelib_q.md#basevalidateoptions)
- [blockUI](corelib_q.md#blockui)
- [blockUndo](corelib_q.md#blockundo)
- [bsModalMarkup](corelib_q.md#bsmodalmarkup)
- [canLoadScriptData](corelib_q.md#canloadscriptdata)
- [cast](corelib_q.md#cast)
- [centerDialog](corelib_q.md#centerdialog)
- [clearKeys](corelib_q.md#clearkeys)
- [clearOptions](corelib_q.md#clearoptions)
- [closePanel](corelib_q.md#closepanel)
- [coalesce](corelib_q.md#coalesce)
- [compareStringFactory](corelib_q.md#comparestringfactory)
- [confirm](corelib_q.md#confirm)
- [confirmDialog](corelib_q.md#confirmdialog)
- [count](corelib_q.md#count)
- [dbText](corelib_q.md#dbtext)
- [dbTryText](corelib_q.md#dbtrytext)
- [debounce](corelib_q.md#debounce)
- [deepClone](corelib_q.md#deepclone)
- [delegateCombine](corelib_q.md#delegatecombine)
- [delegateRemove](corelib_q.md#delegateremove)
- [dialogButtonToBS](corelib_q.md#dialogbuttontobs)
- [dialogButtonToUI](corelib_q.md#dialogbuttontoui)
- [endsWith](corelib_q.md#endswith)
- [executeEverytimeWhenVisible](corelib_q.md#executeeverytimewhenvisible)
- [executeOnceWhenVisible](corelib_q.md#executeoncewhenvisible)
- [extend](corelib_q.md#extend)
- [fieldsProxy](corelib_q.md#fieldsproxy)
- [findElementWithRelativeId](corelib_q.md#findelementwithrelativeid)
- [first](corelib_q.md#first)
- [format](corelib_q.md#format)
- [formatDate](corelib_q.md#formatdate)
- [formatDayHourAndMin](corelib_q.md#formatdayhourandmin)
- [formatISODateTimeUTC](corelib_q.md#formatisodatetimeutc)
- [formatNumber](corelib_q.md#formatnumber)
- [getAttributes](corelib_q.md#getattributes)
- [getBaseType](corelib_q.md#getbasetype)
- [getColumns](corelib_q.md#getcolumns)
- [getColumnsAsync](corelib_q.md#getcolumnsasync)
- [getColumnsData](corelib_q.md#getcolumnsdata)
- [getColumnsDataAsync](corelib_q.md#getcolumnsdataasync)
- [getCookie](corelib_q.md#getcookie)
- [getForm](corelib_q.md#getform)
- [getFormAsync](corelib_q.md#getformasync)
- [getFormData](corelib_q.md#getformdata)
- [getFormDataAsync](corelib_q.md#getformdataasync)
- [getGlobalThis](corelib_q.md#getglobalthis)
- [getHighlightTarget](corelib_q.md#gethighlighttarget)
- [getInstanceType](corelib_q.md#getinstancetype)
- [getLookup](corelib_q.md#getlookup)
- [getLookupAsync](corelib_q.md#getlookupasync)
- [getMembers](corelib_q.md#getmembers)
- [getNested](corelib_q.md#getnested)
- [getRemoteData](corelib_q.md#getremotedata)
- [getRemoteDataAsync](corelib_q.md#getremotedataasync)
- [getStateStore](corelib_q.md#getstatestore)
- [getTemplate](corelib_q.md#gettemplate)
- [getTemplateAsync](corelib_q.md#gettemplateasync)
- [getType](corelib_q.md#gettype)
- [getTypeFullName](corelib_q.md#gettypefullname)
- [getTypeNameProp](corelib_q.md#gettypenameprop)
- [getTypeShortName](corelib_q.md#gettypeshortname)
- [getTypes](corelib_q.md#gettypes)
- [groupBy](corelib_q.md#groupby)
- [htmlEncode](corelib_q.md#htmlencode)
- [iframeDialog](corelib_q.md#iframedialog)
- [indexOf](corelib_q.md#indexof)
- [information](corelib_q.md#information)
- [informationDialog](corelib_q.md#informationdialog)
- [initFormType](corelib_q.md#initformtype)
- [initFullHeightGridPage](corelib_q.md#initfullheightgridpage)
- [initializeTypes](corelib_q.md#initializetypes)
- [insert](corelib_q.md#insert)
- [isArray](corelib_q.md#isarray)
- [isAssignableFrom](corelib_q.md#isassignablefrom)
- [isBS3](corelib_q.md#isbs3)
- [isBS5Plus](corelib_q.md#isbs5plus)
- [isEmptyOrNull](corelib_q.md#isemptyornull)
- [isEnum](corelib_q.md#isenum)
- [isInstanceOfType](corelib_q.md#isinstanceoftype)
- [isMobileView](corelib_q.md#ismobileview)
- [isTrimmedEmpty](corelib_q.md#istrimmedempty)
- [isValue](corelib_q.md#isvalue)
- [keyOf](corelib_q.md#keyof)
- [layoutFillHeight](corelib_q.md#layoutfillheight)
- [layoutFillHeightValue](corelib_q.md#layoutfillheightvalue)
- [loadValidationErrorMessages](corelib_q.md#loadvalidationerrormessages)
- [localText](corelib_q.md#localtext)
- [localeFormat](corelib_q.md#localeformat)
- [newBodyDiv](corelib_q.md#newbodydiv)
- [notifyError](corelib_q.md#notifyerror)
- [notifyInfo](corelib_q.md#notifyinfo)
- [notifySuccess](corelib_q.md#notifysuccess)
- [notifyWarning](corelib_q.md#notifywarning)
- [openPanel](corelib_q.md#openpanel)
- [outerHtml](corelib_q.md#outerhtml)
- [padLeft](corelib_q.md#padleft)
- [parseCriteria](corelib_q.md#parsecriteria)
- [parseDate](corelib_q.md#parsedate)
- [parseDayHourAndMin](corelib_q.md#parsedayhourandmin)
- [parseDecimal](corelib_q.md#parsedecimal)
- [parseHourAndMin](corelib_q.md#parsehourandmin)
- [parseISODateTime](corelib_q.md#parseisodatetime)
- [parseInteger](corelib_q.md#parseinteger)
- [parseQueryString](corelib_q.md#parsequerystring)
- [positionToastContainer](corelib_q.md#positiontoastcontainer)
- [postToService](corelib_q.md#posttoservice)
- [postToUrl](corelib_q.md#posttourl)
- [prefixedText](corelib_q.md#prefixedtext)
- [prop](corelib_q.md#prop)
- [proxyTexts](corelib_q.md#proxytexts)
- [registerClass](corelib_q.md#registerclass)
- [registerEditor](corelib_q.md#registereditor)
- [registerEnum](corelib_q.md#registerenum)
- [registerInterface](corelib_q.md#registerinterface)
- [reloadLookup](corelib_q.md#reloadlookup)
- [reloadLookupAsync](corelib_q.md#reloadlookupasync)
- [removeValidationRule](corelib_q.md#removevalidationrule)
- [replaceAll](corelib_q.md#replaceall)
- [resolveUrl](corelib_q.md#resolveurl)
- [round](corelib_q.md#round)
- [safeCast](corelib_q.md#safecast)
- [serviceCall](corelib_q.md#servicecall)
- [serviceRequest](corelib_q.md#servicerequest)
- [setEquality](corelib_q.md#setequality)
- [setTypeNameProp](corelib_q.md#settypenameprop)
- [single](corelib_q.md#single)
- [splitDateString](corelib_q.md#splitdatestring)
- [startsWith](corelib_q.md#startswith)
- [success](corelib_q.md#success)
- [successDialog](corelib_q.md#successdialog)
- [text](corelib_q.md#text)
- [toGrouping](corelib_q.md#togrouping)
- [toId](corelib_q.md#toid)
- [toSingleLine](corelib_q.md#tosingleline)
- [today](corelib_q.md#today)
- [toggleClass](corelib_q.md#toggleclass)
- [triggerLayoutOnShow](corelib_q.md#triggerlayoutonshow)
- [trim](corelib_q.md#trim)
- [trimEnd](corelib_q.md#trimend)
- [trimStart](corelib_q.md#trimstart)
- [trimToEmpty](corelib_q.md#trimtoempty)
- [trimToNull](corelib_q.md#trimtonull)
- [trunc](corelib_q.md#trunc)
- [tryFirst](corelib_q.md#tryfirst)
- [tryGetText](corelib_q.md#trygettext)
- [turkishLocaleCompare](corelib_q.md#turkishlocalecompare)
- [turkishLocaleToLower](corelib_q.md#turkishlocaletolower)
- [turkishLocaleToUpper](corelib_q.md#turkishlocaletoupper)
- [validateForm](corelib_q.md#validateform)
- [validateOptions](corelib_q.md#validateoptions)
- [validatorAbortHandler](corelib_q.md#validatoraborthandler)
- [warning](corelib_q.md#warning)
- [warningDialog](corelib_q.md#warningdialog)
- [zeroPad](corelib_q.md#zeropad)

## Type Aliases

### Dictionary

Ƭ **Dictionary**<`TItem`\>: `Object`

#### Type parameters

| Name |
| :------ |
| `TItem` |

#### Index signature

▪ [key: `string`]: `TItem`

#### Defined in

[src/q/system.ts:1](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L1)

___

### GroupByElement

Ƭ **GroupByElement**<`TItem`\>: `Object`

A group item returned by `groupBy()`.

#### Type parameters

| Name |
| :------ |
| `TItem` |

#### Type declaration

| Name | Type | Description |
| :------ | :------ | :------ |
| `items` | `TItem`[] | the items in the group |
| `key` | `string` | key of the group |
| `order` | `number` | index of the item in `inOrder` array |
| `start` | `number` | index of the first item of this group in the original array |

#### Defined in

[src/q/arrays.ts:43](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/arrays.ts#L43)

___

### GroupByResult

Ƭ **GroupByResult**<`TItem`\>: `Object`

Return type of the `groupBy` function.

#### Type parameters

| Name |
| :------ |
| `TItem` |

#### Type declaration

| Name | Type |
| :------ | :------ |
| `byKey` | { `[key: string]`: [`GroupByElement`](corelib_q.md#groupbyelement)<`TItem`\>;  } |
| `inOrder` | [`GroupByElement`](corelib_q.md#groupbyelement)<`TItem`\>[] |

#### Defined in

[src/q/arrays.ts:57](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/arrays.ts#L57)

___

### Grouping

Ƭ **Grouping**<`TItem`\>: `Object`

#### Type parameters

| Name |
| :------ |
| `TItem` |

#### Index signature

▪ [key: `string`]: `TItem`[]

#### Defined in

[src/q/arrays.ts:169](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/arrays.ts#L169)

___

### NotifyMap

Ƭ **NotifyMap**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `iconClass` | `string` |
| `message?` | `string` |
| `title?` | `string` |
| `type` | `string` |

#### Defined in

[src/q/toastr2.ts:40](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/toastr2.ts#L40)

___

### ToastContainerOptions

Ƭ **ToastContainerOptions**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `containerId?` | `string` |
| `positionClass?` | `string` |
| `target?` | `string` |

#### Defined in

[src/q/toastr2.ts:5](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/toastr2.ts#L5)

___

### ToastrOptions

Ƭ **ToastrOptions**: [`ToastContainerOptions`](corelib_q.md#toastcontaineroptions) & { `closeButton?`: `boolean` ; `closeClass?`: `string` ; `closeDuration?`: `number` \| ``false`` ; `closeEasing?`: `boolean` ; `closeHtml?`: `string` ; `closeMethod?`: `boolean` ; `closeOnHover?`: `boolean` ; `escapeHtml?`: `boolean` ; `extendedTimeOut?`: `number` ; `hideDuration?`: `number` ; `iconClass?`: `string` ; `messageClass?`: `string` ; `newestOnTop?`: `boolean` ; `onCloseClick?`: (`event`: `Event`) => `void` ; `onHidden?`: () => `void` ; `onShown?`: () => `void` ; `onclick?`: (`event`: `MouseEvent`) => `void` ; `positionClass?`: `string` ; `preventDuplicates?`: `boolean` ; `rtl?`: `boolean` ; `showDuration?`: `number` ; `tapToDismiss?`: `boolean` ; `target?`: `string` ; `timeOut?`: `number` ; `titleClass?`: `string` ; `toastClass?`: `string`  }

#### Defined in

[src/q/toastr2.ts:11](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/toastr2.ts#L11)

___

### Type

Ƭ **Type**: `Function` \| `Object`

#### Defined in

[src/q/system.ts:84](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L84)

## Variables

### Config

• **Config**: `Object`

#### Type declaration

| Name | Type | Description |
| :------ | :------ | :------ |
| `applicationPath` | `string` | This is the root path of your application. If your application resides under http://localhost/mysite/, your root path is "mysite/". This variable is automatically initialized by reading from a <link> element with ID "ApplicationPath" from current page, which is usually located in your _LayoutHead.cshtml file |
| `bootstrapMessages` | `boolean` | Set this to true, to prefer bootstrap dialogs over jQuery UI dialogs by default for message dialogs |
| `emailAllowOnlyAscii` | `boolean` | Email validation by default only allows ASCII characters. Set this to true if you want to allow unicode. |
| `notLoggedInHandler` | `Function` | This is an optional method for handling when user is not logged in. If a users session is expired and when a NotAuthorized response is received from a service call, Serenity will call this handler, so you may intercept it and notify user about this situation and ask if she wants to login again... |
| `responsiveDialogs` | `boolean` | **`Obsolete`** defaulted to false before for backward compatibility, now it is true by default |
| `rootNamespaces` | `string`[] | This is the list of root namespaces that may be searched for types. For example, if you specify an editor type of "MyEditor", first a class with name "MyEditor" will be searched, if not found, search will be followed by "Serenity.MyEditor" and "MyApp.MyEditor" if you added "MyApp" to the list of root namespaces. You should usually add your application root namespace to this list in ScriptInit(ialization).ts file. |

#### Defined in

[src/q/config.ts:1](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/config.ts#L1)

___

### Culture

• **Culture**: [`Locale`](../interfaces/corelib_q.Locale.md)

Current culture, e.g. CultureInfo.CurrentCulture. This is overridden by
settings passed from a `<script>` element in the page with id `ScriptCulture`
containing a JSON object if available. This element is generally created in 
the _LayoutHead.cshtml file for Serenity applications, so that the culture
settings determined server, can be passed to the client.

#### Defined in

[src/q/formatting.ts:132](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L132)

___

### Invariant

• **Invariant**: [`Locale`](../interfaces/corelib_q.Locale.md)

Invariant locale (e.g. CultureInfo.InvariantCulture)

#### Defined in

[src/q/formatting.ts:64](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L64)

___

### defaultNotifyOptions

• **defaultNotifyOptions**: [`ToastrOptions`](corelib_q.md#toastroptions)

#### Defined in

[src/q/notify.ts:10](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/notify.ts#L10)

## Functions

### Criteria

▸ **Criteria**(`field`): [`CriteriaBuilder`](../classes/corelib_q.CriteriaBuilder.md)

Creates a new criteria builder containg the passed field name.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `field` | `string` | The field name. |

#### Returns

[`CriteriaBuilder`](../classes/corelib_q.CriteriaBuilder.md)

#### Defined in

[src/q/criteria.ts:750](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/criteria.ts#L750)

___

### addAttribute

▸ **addAttribute**(`type`, `attr`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `any` |
| `attr` | `any` |

#### Returns

`void`

#### Defined in

[src/q/system.ts:605](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L605)

___

### addEmptyOption

▸ **addEmptyOption**(`select`): `void`

Adds an empty option to the select.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `select` | `JQuery` \| `HTMLSelectElement` | the select element |

#### Returns

`void`

#### Defined in

[src/q/html.ts:8](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/html.ts#L8)

___

### addOption

▸ **addOption**(`select`, `key`, `text`): `void`

Adds an option to the select.

#### Parameters

| Name | Type |
| :------ | :------ |
| `select` | `JQuery` \| `HTMLSelectElement` |
| `key` | `string` |
| `text` | `string` |

#### Returns

`void`

#### Defined in

[src/q/html.ts:15](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/html.ts#L15)

___

### addTypeMember

▸ **addTypeMember**(`type`, `member`): [`TypeMember`](../interfaces/corelib_q.TypeMember.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `any` |
| `member` | [`TypeMember`](../interfaces/corelib_q.TypeMember.md) |

#### Returns

[`TypeMember`](../interfaces/corelib_q.TypeMember.md)

#### Defined in

[src/q/system.ts:279](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L279)

___

### addValidationRule

▸ **addValidationRule**(`element`, `eventClass`, `rule`): `JQuery`

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `JQuery` |
| `eventClass` | `string` |
| `rule` | (`p1`: `JQuery`) => `string` |

#### Returns

`JQuery`

#### Defined in

[src/q/validation.ts:234](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/validation.ts#L234)

___

### alert

▸ **alert**(`message`, `options?`): `void`

**`Obsolete`**

use alertDialog

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `options?` | [`AlertOptions`](../interfaces/corelib_q.AlertOptions.md) |

#### Returns

`void`

#### Defined in

[src/q/dialogs.ts:328](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L328)

___

### alertDialog

▸ **alertDialog**(`message`, `options?`): `void`

Displays an alert dialog

**`See`**

AlertOptions

**`Example`**

```ts
alertDialog("An error occured!"); }
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `message` | `string` | The message to display |
| `options?` | [`AlertOptions`](../interfaces/corelib_q.AlertOptions.md) | Additional options. |

#### Returns

`void`

#### Defined in

[src/q/dialogs.ts:328](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L328)

___

### any

▸ **any**<`TItem`\>(`array`, `predicate`): `boolean`

Tests if any of array elements matches given predicate. Prefer Array.some() over this function (e.g. `[1, 2, 3].some(predicate)`).

#### Type parameters

| Name |
| :------ |
| `TItem` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `array` | `TItem`[] | Array to test. |
| `predicate` | (`x`: `TItem`) => `boolean` | Predicate to test elements. |

#### Returns

`boolean`

True if any element matches.

#### Defined in

[src/q/arrays.ts:7](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/arrays.ts#L7)

___

### attrEncode

▸ **attrEncode**(`s`): `string`

**`Obsolete`**

use htmlEncode as it also encodes quotes

#### Parameters

| Name | Type |
| :------ | :------ |
| `s` | `any` |

#### Returns

`string`

#### Defined in

[src/q/html.ts:100](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/html.ts#L100)

___

### baseValidateOptions

▸ **baseValidateOptions**(): `JQueryValidation.ValidationOptions`

#### Returns

`JQueryValidation.ValidationOptions`

#### Defined in

[src/q/validation.ts:157](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/validation.ts#L157)

___

### blockUI

▸ **blockUI**(`options`): `void`

Uses jQuery BlockUI plugin to block access to whole page (default) or 
a part of it, by using a transparent overlay covering the whole area.

**`Remarks`**

If options are not specified, this function blocks 
whole page with a transparent overlay. Default z-order of the overlay
div is 2000, so a higher z-order shouldn't be used in page.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `options` | [`JQBlockUIOptions`](../interfaces/corelib_q.JQBlockUIOptions.md) | Parameters for the BlockUI plugin |

#### Returns

`void`

#### Defined in

[src/q/blockui.ts:36](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/blockui.ts#L36)

___

### blockUndo

▸ **blockUndo**(): `void`

Unblocks the page.

#### Returns

`void`

#### Defined in

[src/q/blockui.ts:60](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/blockui.ts#L60)

___

### bsModalMarkup

▸ **bsModalMarkup**(`title`, `body`, `modalClass?`, `escapeHtml?`): `HTMLDivElement`

Builds HTML DIV element for a Bootstrap modal dialog

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `title` | `string` | `undefined` | Modal title |
| `body` | `string` | `undefined` | Modal body, it will not be HTML encoded, so make sure it is encoded |
| `modalClass?` | `string` | `undefined` | Optional class to add to the modal element |
| `escapeHtml` | `boolean` | `true` | True to html encode body, default is true |

#### Returns

`HTMLDivElement`

#### Defined in

[src/q/dialogs.ts:147](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L147)

___

### canLoadScriptData

▸ **canLoadScriptData**(`name`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`boolean`

#### Defined in

[src/q/scriptdata.ts:270](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L270)

___

### cast

▸ **cast**(`instance`, `type`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `instance` | `any` |
| `type` | [`Type`](corelib_q.md#type) |

#### Returns

`any`

#### Defined in

[src/q/system.ts:195](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L195)

___

### centerDialog

▸ **centerDialog**(`el`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `el` | `JQuery` |

#### Returns

`void`

#### Defined in

[src/q/layout.ts:99](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/layout.ts#L99)

___

### clearKeys

▸ **clearKeys**(`d`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `d` | `any` |

#### Returns

`void`

#### Defined in

[src/q/system.ts:335](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L335)

___

### clearOptions

▸ **clearOptions**(`select`): `void`

Clears the options in the select element

#### Parameters

| Name | Type |
| :------ | :------ |
| `select` | `JQuery` |

#### Returns

`void`

#### Defined in

[src/q/html.ts:23](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/html.ts#L23)

___

### closePanel

▸ **closePanel**(`element`, `e?`): `void`

Closes a panel, triggering panelbeforeclose and panelclose events on the panel element.
If the panelbeforeclose prevents the default, the operation is cancelled.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `element` | `HTMLElement` \| `JQuery` | The panel element |
| `e?` | `Event` | The event triggering the close |

#### Returns

`void`

#### Defined in

[src/q/dialogs.ts:602](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L602)

___

### coalesce

▸ **coalesce**(`a`, `b`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `any` |
| `b` | `any` |

#### Returns

`any`

#### Defined in

[src/q/system.ts:3](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L3)

___

### compareStringFactory

▸ **compareStringFactory**(`order`): (`a`: `string`, `b`: `string`) => `number`

Factory for a function that compares two strings, based on a character order 
passed in the `order` argument.

#### Parameters

| Name | Type |
| :------ | :------ |
| `order` | `string` |

#### Returns

`fn`

▸ (`a`, `b`): `number`

##### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `string` |
| `b` | `string` |

##### Returns

`number`

#### Defined in

[src/q/formatting.ts:92](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L92)

___

### confirm

▸ **confirm**(`message`, `onYes`, `options?`): `void`

**`Obsolete`**

use confirmDialog

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `onYes` | () => `void` |
| `options?` | [`ConfirmOptions`](../interfaces/corelib_q.ConfirmOptions.md) |

#### Returns

`void`

#### Defined in

[src/q/dialogs.ts:396](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L396)

___

### confirmDialog

▸ **confirmDialog**(`message`, `onYes`, `options?`): `void`

Display a confirmation dialog

**`See`**

ConfirmOptions

**`Example`**

```ts
confirmDialog("Are you sure you want to delete?", () => { 
    // do something when yes is clicked
}
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `message` | `string` | The message to display |
| `onYes` | () => `void` | Callback for Yes button click |
| `options?` | [`ConfirmOptions`](../interfaces/corelib_q.ConfirmOptions.md) | Additional options. |

#### Returns

`void`

#### Defined in

[src/q/dialogs.ts:396](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L396)

___

### count

▸ **count**<`TItem`\>(`array`, `predicate`): `number`

Counts number of array elements that matches a given predicate.

#### Type parameters

| Name |
| :------ |
| `TItem` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `array` | `TItem`[] | Array to test. |
| `predicate` | (`x`: `TItem`) => `boolean` | Predicate to test elements. |

#### Returns

`number`

#### Defined in

[src/q/arrays.ts:16](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/arrays.ts#L16)

___

### dbText

▸ **dbText**(`prefix`): (`key`: `string`) => `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `prefix` | `string` |

#### Returns

`fn`

▸ (`key`): `string`

##### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

##### Returns

`string`

#### Defined in

[src/q/localtext.ts:15](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/localtext.ts#L15)

___

### dbTryText

▸ **dbTryText**(`prefix`): (`key`: `string`) => `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `prefix` | `string` |

#### Returns

`fn`

▸ (`key`): `string`

##### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

##### Returns

`string`

#### Defined in

[src/q/localtext.ts:57](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/localtext.ts#L57)

___

### debounce

▸ **debounce**<`T`\>(`func`, `wait?`, `immediate?`): [`DebouncedFunction`](../interfaces/corelib_q.DebouncedFunction.md)<`T`\>

Returns a function, that, as long as it continues to be invoked, will not
be triggered. The function also has a property 'clear' that can be used 
to clear the timer to prevent previously scheduled executions, and flush method
to invoke scheduled executions now if any.

**`Source`**

underscore.js

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends (...`args`: `any`) => `any` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `func` | `T` | - |
| `wait?` | `number` | The function will be called after it stops being called for N milliseconds. |
| `immediate?` | `boolean` | If passed, trigger the function on the leading edge, instead of the trailing. |

#### Returns

[`DebouncedFunction`](../interfaces/corelib_q.DebouncedFunction.md)<`T`\>

#### Defined in

[src/q/debounce.ts:39](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/debounce.ts#L39)

___

### deepClone

▸ **deepClone**<`T`\>(`a`, `a2?`, `a3?`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | `any` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `T` |
| `a2?` | `any` |
| `a3?` | `any` |

#### Returns

`T`

#### Defined in

[src/q/system.ts:23](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L23)

___

### delegateCombine

▸ **delegateCombine**(`delegate1`, `delegate2`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `delegate1` | `any` |
| `delegate2` | `any` |

#### Returns

`any`

#### Defined in

[src/q/system.ts:342](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L342)

___

### delegateRemove

▸ **delegateRemove**(`delegate1`, `delegate2`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `delegate1` | `any` |
| `delegate2` | `any` |

#### Returns

`any`

#### Defined in

[src/q/system.ts:454](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L454)

___

### dialogButtonToBS

▸ **dialogButtonToBS**(`x`): `HTMLButtonElement`

Converts a `DialogButton` declaration to Bootstrap button element

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `x` | [`DialogButton`](../interfaces/corelib_q.DialogButton.md) | Dialog button declaration |

#### Returns

`HTMLButtonElement`

Bootstrap button element

#### Defined in

[src/q/dialogs.ts:172](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L172)

___

### dialogButtonToUI

▸ **dialogButtonToUI**(`x`): `any`

Converts a `DialogButton` declaration to jQuery UI button type

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `x` | [`DialogButton`](../interfaces/corelib_q.DialogButton.md) | Dialog button declaration |

#### Returns

`any`

jQuery UI button type

#### Defined in

[src/q/dialogs.ts:191](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L191)

___

### endsWith

▸ **endsWith**(`s`, `suffix`): `boolean`

Checks if the string ends with the specified substring.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `s` | `string` | String to check. |
| `suffix` | `string` | Suffix to check. |

#### Returns

`boolean`

True if the string ends with the specified substring.

#### Defined in

[src/q/strings.ts:7](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/strings.ts#L7)

___

### executeEverytimeWhenVisible

▸ **executeEverytimeWhenVisible**(`element`, `callback`, `callNowIfVisible`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `JQuery` |
| `callback` | `Function` |
| `callNowIfVisible` | `boolean` |

#### Returns

`void`

#### Defined in

[src/q/layouttimer.ts:154](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/layouttimer.ts#L154)

___

### executeOnceWhenVisible

▸ **executeOnceWhenVisible**(`element`, `callback`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `JQuery` |
| `callback` | `Function` |

#### Returns

`void`

#### Defined in

[src/q/layouttimer.ts:138](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/layouttimer.ts#L138)

___

### extend

▸ **extend**<`T`\>(`a`, `b`): `T`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | `any` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `T` |
| `b` | `T` |

#### Returns

`T`

#### Defined in

[src/q/system.ts:16](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L16)

___

### fieldsProxy

▸ **fieldsProxy**<`TRow`\>(): `Readonly`<`Record`<keyof `TRow`, `string`\>\>

#### Type parameters

| Name |
| :------ |
| `TRow` |

#### Returns

`Readonly`<`Record`<keyof `TRow`, `string`\>\>

#### Defined in

[src/q/system.ts:538](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L538)

___

### findElementWithRelativeId

▸ **findElementWithRelativeId**(`element`, `relativeId`, `context?`): `JQuery`

Finds the first element with the given relative id to the source element.
It can handle underscores in the source element id.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `element` | `JQuery` | the source element |
| `relativeId` | `string` | the relative id to the source element |
| `context?` | `HTMLElement` | the context element (optional) |

#### Returns

`JQuery`

the element with the given relative id to the source element.

#### Defined in

[src/q/html.ts:35](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/html.ts#L35)

▸ **findElementWithRelativeId**(`element`, `relativeId`, `context?`): `HTMLElement`

Finds the first element with the given relative id to the source element.
It can handle underscores in the source element id.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `element` | `HTMLElement` | the source element |
| `relativeId` | `string` | the relative id to the source element |
| `context?` | `HTMLElement` | the context element (optional) |

#### Returns

`HTMLElement`

the element with the given relative id to the source element.

#### Defined in

[src/q/html.ts:44](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/html.ts#L44)

___

### first

▸ **first**<`TItem`\>(`array`, `predicate`): `TItem`

Gets first element in an array that matches given predicate similar to LINQ's First.
Throws an error if no match is found.

#### Type parameters

| Name |
| :------ |
| `TItem` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `array` | `TItem`[] | Array to test. |
| `predicate` | (`x`: `TItem`) => `boolean` | Predicate to test elements. |

#### Returns

`TItem`

First element that matches.

#### Defined in

[src/q/arrays.ts:32](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/arrays.ts#L32)

___

### format

▸ **format**(`format`, `...prm`): `string`

Formats a string with parameters similar to .NET's String.Format function
using current `Culture` locale settings.

#### Parameters

| Name | Type |
| :------ | :------ |
| `format` | `string` |
| `...prm` | `any`[] |

#### Returns

`string`

#### Defined in

[src/q/formatting.ts:265](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L265)

___

### formatDate

▸ **formatDate**(`d`, `format?`, `locale?`): `string`

Formats a date using the specified format string and optional culture.
Supports .NET style format strings including custom formats.
See .NET documentation for supported formats.

**`Example`**

```ts
// returns "2019-01-01"
formatDate(new Date(2019, 0, 1), "yyyy-MM-dd");
```

**`Example`**

```ts
// returns "2019-01-01 12:00:00"
formatDate(new Date(2019, 0, 1, 12), "yyyy-MM-dd HH:mm:ss");
```

**`Example`**

```ts
// returns "2019-01-01 12:00:00.000"
formatDate(new Date(2019, 0, 1, 12), "yyyy-MM-dd HH:mm:ss.fff");
```

**`Example`**

```ts
// returns "2019-01-01 12:00:00.000 AM"
formatDate(new Date(2019, 0, 1, 12), "yyyy-MM-dd HH:mm:ss.fff tt");
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `d` | `string` \| `Date` | the date to format. If null, it returns empty string. |
| `format?` | `string` | the format string to use. If null, it uses the current culture's default format. 'G' uses the culture's datetime format. 'g' uses the culture's datetime format with secs removed. 'd' uses the culture's date format. 't' uses the culture's time format. 'u' uses the sortable ISO format with UTC time. 'U' uses the culture's date format with UTC time. |
| `locale?` | [`Locale`](../interfaces/corelib_q.Locale.md) | the locale to use |

#### Returns

`string`

the formatted date

#### Defined in

[src/q/formatting.ts:671](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L671)

___

### formatDayHourAndMin

▸ **formatDayHourAndMin**(`n`): `string`

Formats a number containing number of minutes into a string in the format "d.hh:mm".

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `n` | `number` | The number of minutes. |

#### Returns

`string`

#### Defined in

[src/q/formatting.ts:842](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L842)

___

### formatISODateTimeUTC

▸ **formatISODateTimeUTC**(`d`): `string`

Formats a date as the ISO 8601 UTC date/time format.

#### Parameters

| Name | Type |
| :------ | :------ |
| `d` | `Date` |

#### Returns

`string`

#### Defined in

[src/q/formatting.ts:865](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L865)

___

### formatNumber

▸ **formatNumber**(`num`, `format?`, `decOrLoc?`, `grp?`): `string`

Formats a number using the current `Culture` locale (or the passed locale) settings.
It supports format specifiers similar to .NET numeric formatting strings.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `num` | `number` | the number to format |
| `format?` | `string` | the format specifier. default is 'g'. See .NET numeric formatting strings documentation for more information. |
| `decOrLoc?` | `string` \| [`NumberFormat`](../interfaces/corelib_q.NumberFormat.md) | - |
| `grp?` | `string` | - |

#### Returns

`string`

#### Defined in

[src/q/formatting.ts:318](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L318)

___

### getAttributes

▸ **getAttributes**(`type`, `attrType`, `inherit?`): `any`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `any` |
| `attrType` | `any` |
| `inherit?` | `boolean` |

#### Returns

`any`[]

#### Defined in

[src/q/system.ts:228](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L228)

___

### getBaseType

▸ **getBaseType**(`type`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `any` |

#### Returns

`any`

#### Defined in

[src/q/system.ts:203](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L203)

___

### getColumns

▸ **getColumns**(`key`): [`PropertyItem`](../interfaces/corelib_q.PropertyItem.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

[`PropertyItem`](../interfaces/corelib_q.PropertyItem.md)[]

#### Defined in

[src/q/scriptdata.ts:230](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L230)

___

### getColumnsAsync

▸ **getColumnsAsync**(`key`): `Promise`<[`PropertyItem`](../interfaces/corelib_q.PropertyItem.md)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`Promise`<[`PropertyItem`](../interfaces/corelib_q.PropertyItem.md)[]\>

#### Defined in

[src/q/scriptdata.ts:238](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L238)

___

### getColumnsData

▸ **getColumnsData**(`key`): [`PropertyItemsData`](../interfaces/corelib_q.PropertyItemsData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

[`PropertyItemsData`](../interfaces/corelib_q.PropertyItemsData.md)

#### Defined in

[src/q/scriptdata.ts:234](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L234)

___

### getColumnsDataAsync

▸ **getColumnsDataAsync**(`key`): `Promise`<[`PropertyItemsData`](../interfaces/corelib_q.PropertyItemsData.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`Promise`<[`PropertyItemsData`](../interfaces/corelib_q.PropertyItemsData.md)\>

#### Defined in

[src/q/scriptdata.ts:242](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L242)

___

### getCookie

▸ **getCookie**(`name`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`any`

#### Defined in

[src/q/services.ts:8](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/services.ts#L8)

___

### getForm

▸ **getForm**(`key`): [`PropertyItem`](../interfaces/corelib_q.PropertyItem.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

[`PropertyItem`](../interfaces/corelib_q.PropertyItem.md)[]

#### Defined in

[src/q/scriptdata.ts:246](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L246)

___

### getFormAsync

▸ **getFormAsync**(`key`): `Promise`<[`PropertyItem`](../interfaces/corelib_q.PropertyItem.md)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`Promise`<[`PropertyItem`](../interfaces/corelib_q.PropertyItem.md)[]\>

#### Defined in

[src/q/scriptdata.ts:254](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L254)

___

### getFormData

▸ **getFormData**(`key`): [`PropertyItemsData`](../interfaces/corelib_q.PropertyItemsData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

[`PropertyItemsData`](../interfaces/corelib_q.PropertyItemsData.md)

#### Defined in

[src/q/scriptdata.ts:250](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L250)

___

### getFormDataAsync

▸ **getFormDataAsync**(`key`): `Promise`<[`PropertyItemsData`](../interfaces/corelib_q.PropertyItemsData.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`Promise`<[`PropertyItemsData`](../interfaces/corelib_q.PropertyItemsData.md)\>

#### Defined in

[src/q/scriptdata.ts:258](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L258)

___

### getGlobalThis

▸ **getGlobalThis**(): `any`

#### Returns

`any`

#### Defined in

[src/q/system.ts:116](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L116)

___

### getHighlightTarget

▸ **getHighlightTarget**(`el`): `HTMLElement`

#### Parameters

| Name | Type |
| :------ | :------ |
| `el` | `HTMLElement` |

#### Returns

`HTMLElement`

#### Defined in

[src/q/validation.ts:149](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/validation.ts#L149)

___

### getInstanceType

▸ **getInstanceType**(`instance`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `instance` | `any` |

#### Returns

`any`

#### Defined in

[src/q/system.ts:158](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L158)

___

### getLookup

▸ **getLookup**<`TItem`\>(`key`): [`Lookup`](../classes/corelib_q.Lookup.md)<`TItem`\>

#### Type parameters

| Name |
| :------ |
| `TItem` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

[`Lookup`](../classes/corelib_q.Lookup.md)<`TItem`\>

#### Defined in

[src/q/scriptdata.ts:214](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L214)

___

### getLookupAsync

▸ **getLookupAsync**<`TItem`\>(`key`): `Promise`<[`Lookup`](../classes/corelib_q.Lookup.md)<`TItem`\>\>

#### Type parameters

| Name |
| :------ |
| `TItem` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`Promise`<[`Lookup`](../classes/corelib_q.Lookup.md)<`TItem`\>\>

#### Defined in

[src/q/scriptdata.ts:218](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L218)

___

### getMembers

▸ **getMembers**(`type`, `memberTypes`): [`TypeMember`](../interfaces/corelib_q.TypeMember.md)[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `any` |
| `memberTypes` | [`MemberType`](../enums/corelib_q.MemberType.md) |

#### Returns

[`TypeMember`](../interfaces/corelib_q.TypeMember.md)[]

#### Defined in

[src/q/system.ts:262](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L262)

___

### getNested

▸ **getNested**(`from`, `name`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `from` | `any` |
| `name` | `string` |

#### Returns

`any`

#### Defined in

[src/q/system.ts:98](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L98)

___

### getRemoteData

▸ **getRemoteData**<`TData`\>(`key`): `TData`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `any` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`TData`

#### Defined in

[src/q/scriptdata.ts:206](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L206)

___

### getRemoteDataAsync

▸ **getRemoteDataAsync**<`TData`\>(`key`): `Promise`<`TData`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | `any` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`Promise`<`TData`\>

#### Defined in

[src/q/scriptdata.ts:210](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L210)

___

### getStateStore

▸ **getStateStore**(`key?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `key?` | `string` |

#### Returns

`any`

#### Defined in

[src/q/system.ts:365](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L365)

___

### getTemplate

▸ **getTemplate**(`key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`string`

#### Defined in

[src/q/scriptdata.ts:262](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L262)

___

### getTemplateAsync

▸ **getTemplateAsync**(`key`): `Promise`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`Promise`<`string`\>

#### Defined in

[src/q/scriptdata.ts:266](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L266)

___

### getType

▸ **getType**(`name`, `target?`): [`Type`](corelib_q.md#type)

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `target?` | `any` |

#### Returns

[`Type`](corelib_q.md#type)

#### Defined in

[src/q/system.ts:120](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L120)

___

### getTypeFullName

▸ **getTypeFullName**(`type`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | [`Type`](corelib_q.md#type) |

#### Returns

`string`

#### Defined in

[src/q/system.ts:146](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L146)

___

### getTypeNameProp

▸ **getTypeNameProp**(`type`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | [`Type`](corelib_q.md#type) |

#### Returns

`string`

#### Defined in

[src/q/system.ts:138](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L138)

___

### getTypeShortName

▸ **getTypeShortName**(`type`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | [`Type`](corelib_q.md#type) |

#### Returns

`string`

#### Defined in

[src/q/system.ts:151](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L151)

___

### getTypes

▸ **getTypes**(`from?`): `any`[]

#### Parameters

| Name | Type |
| :------ | :------ |
| `from?` | `any` |

#### Returns

`any`[]

#### Defined in

[src/q/system.ts:310](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L310)

___

### groupBy

▸ **groupBy**<`TItem`\>(`items`, `getKey`): [`GroupByResult`](corelib_q.md#groupbyresult)<`TItem`\>

Groups an array with keys determined by specified getKey() callback.
Resulting object contains group objects in order and a dictionary to access by key.
This is similar to LINQ's ToLookup function with some additional details like start index.

#### Type parameters

| Name |
| :------ |
| `TItem` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `items` | `TItem`[] | Array to group. |
| `getKey` | (`x`: `TItem`) => `any` | Function that returns key for each item. |

#### Returns

[`GroupByResult`](corelib_q.md#groupbyresult)<`TItem`\>

GroupByResult object.

#### Defined in

[src/q/arrays.ts:70](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/arrays.ts#L70)

___

### htmlEncode

▸ **htmlEncode**(`s`): `string`

Html encodes a string (encodes single and double quotes, & (ampersand), > and < characters)

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `s` | `any` | String (or number etc.) to be HTML encoded |

#### Returns

`string`

#### Defined in

[src/q/html.ts:100](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/html.ts#L100)

___

### iframeDialog

▸ **iframeDialog**(`options`): `void`

Display a dialog that shows an HTML block in an IFRAME, which is usually returned from server callbacks

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `options` | [`IFrameDialogOptions`](../interfaces/corelib_q.IFrameDialogOptions.md) | The options |

#### Returns

`void`

#### Defined in

[src/q/dialogs.ts:465](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L465)

___

### indexOf

▸ **indexOf**<`TItem`\>(`array`, `predicate`): `number`

Gets index of first element in an array that matches given predicate.

#### Type parameters

| Name |
| :------ |
| `TItem` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `array` | `TItem`[] | Array to test. |
| `predicate` | (`x`: `TItem`) => `boolean` | Predicate to test elements. |

#### Returns

`number`

#### Defined in

[src/q/arrays.ts:103](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/arrays.ts#L103)

___

### information

▸ **information**(`message`, `onOk?`, `options?`): `void`

**`Obsolete`**

use informationDialog

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `onOk?` | () => `void` |
| `options?` | [`ConfirmOptions`](../interfaces/corelib_q.ConfirmOptions.md) |

#### Returns

`void`

#### Defined in

[src/q/dialogs.ts:525](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L525)

___

### informationDialog

▸ **informationDialog**(`message`, `onOk?`, `options?`): `void`

Display an information dialog

**`See`**

ConfirmOptions

**`Example`**

```ts
informationDialog("Operation complete", () => { 
    // do something when OK is clicked
}
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `message` | `string` | The message to display |
| `onOk?` | () => `void` | Callback for OK button click |
| `options?` | [`ConfirmOptions`](../interfaces/corelib_q.ConfirmOptions.md) | Additional options. |

#### Returns

`void`

#### Defined in

[src/q/dialogs.ts:525](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L525)

___

### initFormType

▸ **initFormType**(`typ`, `nameWidgetPairs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `typ` | `Function` |
| `nameWidgetPairs` | `any`[] |

#### Returns

`void`

#### Defined in

[src/q/system.ts:492](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L492)

___

### initFullHeightGridPage

▸ **initFullHeightGridPage**(`gridDiv`, `opt?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `gridDiv` | `HTMLElement` \| `JQuery` |
| `opt?` | `Object` |
| `opt.noRoute?` | `boolean` |
| `opt.setHeight?` | `boolean` |

#### Returns

`void`

#### Defined in

[src/q/layout.ts:7](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/layout.ts#L7)

___

### initializeTypes

▸ **initializeTypes**(`root`, `pre`, `limit`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `root` | `any` |
| `pre` | `string` |
| `limit` | `number` |

#### Returns

`void`

#### Defined in

[src/q/system.ts:621](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L621)

___

### insert

▸ **insert**(`obj`, `index`, `item`): `void`

Inserts an item to the array at specified index. Prefer Array.splice unless
you need to support IE.

**`Throws`**

Error if object does not support insert.

**`Example`**

```ts
insert([1, 2, 3], 1, 4); // [1, 4, 2, 3]
insert({ insert: (index, item) => { this.splice(index, 0, item); } }
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `obj` | `any` | Array or array like object to insert to. |
| `index` | `number` | Index to insert at. |
| `item` | `any` | Item to insert. |

#### Returns

`void`

#### Defined in

[src/q/arrays.ts:122](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/arrays.ts#L122)

___

### isArray

▸ **isArray**(`arg`): arg is any[]

Determines if the object is an array. Prefer Array.isArray over this function (e.g. `Array.isArray(obj)`).

**`Example`**

```ts
isArray([1, 2, 3]); // true
isArray({}); // false
```

#### Parameters

| Name | Type |
| :------ | :------ |
| `arg` | `any` |

#### Returns

arg is any[]

True if the object is an array.

#### Defined in

../../../../../Users/volka/AppData/Local/pnpm/global/5/.pnpm/typescript@4.9.3/node_modules/typescript/lib/lib.es5.d.ts:1491

___

### isAssignableFrom

▸ **isAssignableFrom**(`target`, `type`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `target` | `any` |
| `type` | [`Type`](corelib_q.md#type) |

#### Returns

`boolean`

#### Defined in

[src/q/system.ts:171](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L171)

___

### isBS3

▸ **isBS3**(): `boolean`

Returns true if Bootstrap 3 is loaded

#### Returns

`boolean`

#### Defined in

[src/q/dialogs.ts:109](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L109)

___

### isBS5Plus

▸ **isBS5Plus**(): `boolean`

Returns true if Bootstrap 5+ is loaded

#### Returns

`boolean`

#### Defined in

[src/q/dialogs.ts:117](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L117)

___

### isEmptyOrNull

▸ **isEmptyOrNull**(`s`): `boolean`

Checks if the string is empty or null.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `s` | `string` | String to check. |

#### Returns

`boolean`

True if the string is empty or null.

#### Defined in

[src/q/strings.ts:16](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/strings.ts#L16)

___

### isEnum

▸ **isEnum**(`type`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `any` |

#### Returns

`boolean`

#### Defined in

[src/q/system.ts:487](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L487)

___

### isInstanceOfType

▸ **isInstanceOfType**(`instance`, `type`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `instance` | `any` |
| `type` | [`Type`](corelib_q.md#type) |

#### Returns

`boolean`

#### Defined in

[src/q/system.ts:181](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L181)

___

### isMobileView

▸ **isMobileView**(): `boolean`

#### Returns

`boolean`

#### Defined in

[src/q/layout.ts:69](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/layout.ts#L69)

___

### isTrimmedEmpty

▸ **isTrimmedEmpty**(`s`): `boolean`

Checks if the string is empty or null or whitespace.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `s` | `string` | String to check. |

#### Returns

`boolean`

True if the string is empty or null or whitespace.

#### Defined in

[src/q/strings.ts:25](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/strings.ts#L25)

___

### isValue

▸ **isValue**(`a`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `any` |

#### Returns

`boolean`

#### Defined in

[src/q/system.ts:7](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L7)

___

### keyOf

▸ **keyOf**<`T`\>(`prop`): keyof `T`

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `prop` | keyof `T` |

#### Returns

keyof `T`

#### Defined in

[src/q/system.ts:542](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L542)

___

### layoutFillHeight

▸ **layoutFillHeight**(`element`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `JQuery` |

#### Returns

`void`

#### Defined in

[src/q/layout.ts:61](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/layout.ts#L61)

___

### layoutFillHeightValue

▸ **layoutFillHeightValue**(`element`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `JQuery` |

#### Returns

`number`

#### Defined in

[src/q/layout.ts:46](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/layout.ts#L46)

___

### loadValidationErrorMessages

▸ **loadValidationErrorMessages**(): `void`

#### Returns

`void`

#### Defined in

[src/q/validation.ts:116](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/validation.ts#L116)

___

### localText

▸ **localText**(`key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`string`

#### Defined in

[src/q/localtext.ts:4](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/localtext.ts#L4)

___

### localeFormat

▸ **localeFormat**(`l`, `format`, `...prm`): `string`

Formats a string with parameters similar to .NET's String.Format function
using the locale passed as the first argument.

#### Parameters

| Name | Type |
| :------ | :------ |
| `l` | [`Locale`](../interfaces/corelib_q.Locale.md) |
| `format` | `string` |
| `...prm` | `any`[] |

#### Returns

`string`

#### Defined in

[src/q/formatting.ts:273](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L273)

___

### newBodyDiv

▸ **newBodyDiv**(): `JQuery`

Creates a new DIV and appends it to the body.

#### Returns

`JQuery`

the new DIV element.

#### Defined in

[src/q/html.ts:114](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/html.ts#L114)

___

### notifyError

▸ **notifyError**(`message`, `title?`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `title?` | `string` |
| `options?` | [`ToastrOptions`](corelib_q.md#toastroptions) |

#### Returns

`void`

#### Defined in

[src/q/notify.ts:78](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/notify.ts#L78)

___

### notifyInfo

▸ **notifyInfo**(`message`, `title?`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `title?` | `string` |
| `options?` | [`ToastrOptions`](corelib_q.md#toastroptions) |

#### Returns

`void`

#### Defined in

[src/q/notify.ts:74](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/notify.ts#L74)

___

### notifySuccess

▸ **notifySuccess**(`message`, `title?`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `title?` | `string` |
| `options?` | [`ToastrOptions`](corelib_q.md#toastroptions) |

#### Returns

`void`

#### Defined in

[src/q/notify.ts:70](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/notify.ts#L70)

___

### notifyWarning

▸ **notifyWarning**(`message`, `title?`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `title?` | `string` |
| `options?` | [`ToastrOptions`](corelib_q.md#toastroptions) |

#### Returns

`void`

#### Defined in

[src/q/notify.ts:66](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/notify.ts#L66)

___

### openPanel

▸ **openPanel**(`element`, `uniqueName?`): `void`

Opens a panel, triggering panelbeforeopen and panelopen events on the panel element,
and panelopening and panelopened events on the window.
If the panelbeforeopen prevents the default, the operation is cancelled.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `element` | `HTMLElement` \| `JQuery` | The panel element |
| `uniqueName?` | `string` | A unique name for the panel. If not specified, the panel id is used. If the panel has no id, a timestamp is used. |

#### Returns

`void`

#### Defined in

[src/q/dialogs.ts:674](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L674)

___

### outerHtml

▸ **outerHtml**(`element`): `string`

Returns the outer HTML of the element.

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `JQuery` |

#### Returns

`string`

#### Defined in

[src/q/html.ts:121](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/html.ts#L121)

___

### padLeft

▸ **padLeft**(`s`, `len`, `ch?`): `any`

Pads the string to the left with the specified character.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `s` | `string` \| `number` | `undefined` | String to pad. |
| `len` | `number` | `undefined` | Target length of the string. |
| `ch` | `string` | `' '` | Character to pad with. |

#### Returns

`any`

Padded string.

#### Defined in

[src/q/strings.ts:36](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/strings.ts#L36)

___

### parseCriteria

▸ **parseCriteria**(`expression`, `params?`): `any`[]

Parses a criteria expression to Serenity Criteria array format.
The string may optionally contain parameters like `A >= @p1 and B < @p2`.

**`Example`**

```ts
parseCriteria('A >=
```

**`P1`**

and B < @p2', { p1: 5, p2: 4 }) // [[[a], '>=' 5], 'and', [[b], '<', 4]]

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `expression` | `string` | The criteria expression. |
| `params?` | `any` | The dictionary containing parameter values like { p1: 10, p2: 20 }. |

#### Returns

`any`[]

#### Defined in

[src/q/criteria.ts:694](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/criteria.ts#L694)

▸ **parseCriteria**(`strings`, `...values`): `any`[]

Parses a criteria expression to Serenity Criteria array format.
The expression may contain parameter placeholders like `A >= ${p1}`
where p1 is a variable in the scope.

**`Example`**

```ts
var a = 5, b = 4;
parseCriteria`A >= ${a} and B < ${b}` // [[[a], '>=' 5], 'and', [[b], '<', 4]]
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `strings` | `TemplateStringsArray` | The string fragments. |
| `...values` | `any`[] | The tagged template arguments. |

#### Returns

`any`[]

#### Defined in

[src/q/criteria.ts:705](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/criteria.ts#L705)

___

### parseDate

▸ **parseDate**(`s`, `dateOrder?`): `Date`

Parses a string to a date. If the string is empty or whitespace, returns null.
Returns a NaN Date if the string is not a valid date.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `s` | `string` | The string to parse. |
| `dateOrder?` | `string` | The order of the date parts in the string. Defaults to culture's default date order. |

#### Returns

`Date`

#### Defined in

[src/q/formatting.ts:964](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L964)

___

### parseDayHourAndMin

▸ **parseDayHourAndMin**(`s`): `number`

Parses a string in the format "d.hh:mm" into a number containing number of minutes.
Returns NaN if the hours not in range 0-23 or minutes not in range 0-59.
Returns NULL if the string is empty or whitespace.

#### Parameters

| Name | Type |
| :------ | :------ |
| `s` | `string` |

#### Returns

`number`

#### Defined in

[src/q/formatting.ts:935](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L935)

___

### parseDecimal

▸ **parseDecimal**(`s`): `number`

Converts a string to a decimal. The difference between parseFloat and parseDecimal
is that parseDecimal will return null if the string is empty or null, whereas
parseFloat will return NaN and parseDecimal will use the current culture's group
and decimal separators.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `s` | `string` | the string to parse |

#### Returns

`number`

#### Defined in

[src/q/formatting.ts:574](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L574)

___

### parseHourAndMin

▸ **parseHourAndMin**(`value`): `number`

Parses a time string in the format "hh:mm" into a number containing number of minutes.
Returns NaN if the hours not in range 0-23 or minutes not in range 0-59.

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `string` |

#### Returns

`number`

#### Defined in

[src/q/formatting.ts:908](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L908)

___

### parseISODateTime

▸ **parseISODateTime**(`s`): `Date`

Parses a string in the ISO 8601 UTC date/time format.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `s` | `string` | The string to parse. |

#### Returns

`Date`

#### Defined in

[src/q/formatting.ts:887](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L887)

___

### parseInteger

▸ **parseInteger**(`s`): `number`

Converts a string to an integer. The difference between parseInt and parseInteger 
is that parseInteger will return null if the string is empty or null, whereas
parseInt will return NaN and parseInteger will use the current culture's group
and decimal separators.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `s` | `string` | the string to parse |

#### Returns

`number`

#### Defined in

[src/q/formatting.ts:552](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L552)

___

### parseQueryString

▸ **parseQueryString**(`s?`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `s?` | `string` |

#### Returns

`Object`

#### Defined in

[src/q/services.ts:153](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/services.ts#L153)

___

### positionToastContainer

▸ **positionToastContainer**(`create`, `options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `create` | `boolean` |
| `options?` | [`ToastrOptions`](corelib_q.md#toastroptions) |

#### Returns

`void`

#### Defined in

[src/q/notify.ts:82](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/notify.ts#L82)

___

### postToService

▸ **postToService**(`options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`PostToServiceOptions`](../interfaces/corelib_q.PostToServiceOptions.md) |

#### Returns

`void`

#### Defined in

[src/q/services.ts:169](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/services.ts#L169)

___

### postToUrl

▸ **postToUrl**(`options`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`PostToUrlOptions`](../interfaces/corelib_q.PostToUrlOptions.md) |

#### Returns

`void`

#### Defined in

[src/q/services.ts:191](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/services.ts#L191)

___

### prefixedText

▸ **prefixedText**(`prefix`): (`text`: `string`, `key`: `string` \| (`p?`: `string`) => `string`) => `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `prefix` | `string` |

#### Returns

`fn`

▸ (`text`, `key`): `string`

##### Parameters

| Name | Type |
| :------ | :------ |
| `text` | `string` |
| `key` | `string` \| (`p?`: `string`) => `string` |

##### Returns

`string`

#### Defined in

[src/q/localtext.ts:25](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/localtext.ts#L25)

___

### prop

▸ **prop**(`type`, `name`, `getter?`, `setter?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `any` |
| `name` | `string` |
| `getter?` | `string` |
| `setter?` | `string` |

#### Returns

`void`

#### Defined in

[src/q/system.ts:506](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L506)

___

### proxyTexts

▸ **proxyTexts**(`o`, `p`, `t`): `Object`

#### Parameters

| Name | Type |
| :------ | :------ |
| `o` | `Record`<`string`, `any`\> |
| `p` | `string` |
| `t` | `Record`<`string`, `any`\> |

#### Returns

`Object`

#### Defined in

[src/q/localtext.ts:63](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/localtext.ts#L63)

___

### registerClass

▸ **registerClass**(`type`, `name`, `intf?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `any` |
| `name` | `string` |
| `intf?` | `any`[] |

#### Returns

`void`

#### Defined in

[src/q/system.ts:579](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L579)

___

### registerEditor

▸ **registerEditor**(`type`, `name`, `intf?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `any` |
| `name` | `string` |
| `intf?` | `any`[] |

#### Returns

`void`

#### Defined in

[src/q/system.ts:584](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L584)

___

### registerEnum

▸ **registerEnum**(`type`, `name`, `enumKey?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `any` |
| `name` | `string` |
| `enumKey?` | `string` |

#### Returns

`void`

#### Defined in

[src/q/system.ts:589](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L589)

___

### registerInterface

▸ **registerInterface**(`type`, `name`, `intf?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | `any` |
| `name` | `string` |
| `intf?` | `any`[] |

#### Returns

`void`

#### Defined in

[src/q/system.ts:599](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L599)

___

### reloadLookup

▸ **reloadLookup**<`TItem`\>(`key`): [`Lookup`](../classes/corelib_q.Lookup.md)<`TItem`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TItem` | `any` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

[`Lookup`](../classes/corelib_q.Lookup.md)<`TItem`\>

#### Defined in

[src/q/scriptdata.ts:222](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L222)

___

### reloadLookupAsync

▸ **reloadLookupAsync**<`TItem`\>(`key`): `Promise`<[`Lookup`](../classes/corelib_q.Lookup.md)<`TItem`\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TItem` | `any` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`Promise`<[`Lookup`](../classes/corelib_q.Lookup.md)<`TItem`\>\>

#### Defined in

[src/q/scriptdata.ts:226](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/scriptdata.ts#L226)

___

### removeValidationRule

▸ **removeValidationRule**(`element`, `eventClass`): `JQuery`

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `JQuery` |
| `eventClass` | `string` |

#### Returns

`JQuery`

#### Defined in

[src/q/validation.ts:243](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/validation.ts#L243)

___

### replaceAll

▸ **replaceAll**(`str`, `find`, `replace`): `string`

Replaces all occurrences of the search string with the replacement string.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `str` | `string` | String to replace. |
| `find` | `string` | String to find. |
| `replace` | `string` | String to replace with. |

#### Returns

`string`

Replaced string.

#### Defined in

[src/q/strings.ts:111](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/strings.ts#L111)

___

### resolveUrl

▸ **resolveUrl**(`url`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `url` | `string` |

#### Returns

`string`

#### Defined in

[src/q/services.ts:217](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/services.ts#L217)

___

### round

▸ **round**(`n`, `d?`, `rounding?`): `number`

Rounds a number to specified digits or an integer number if digits are not specified.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `n` | `number` | the number to round |
| `d?` | `number` | the number of digits to round to. default is zero. |
| `rounding?` | `boolean` | whether to use banker's rounding |

#### Returns

`number`

the rounded number

#### Defined in

[src/q/formatting.ts:294](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L294)

___

### safeCast

▸ **safeCast**(`instance`, `type`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `instance` | `any` |
| `type` | [`Type`](corelib_q.md#type) |

#### Returns

`any`

#### Defined in

[src/q/system.ts:191](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L191)

___

### serviceCall

▸ **serviceCall**<`TResponse`\>(`options`): `JQueryXHR`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TResponse` | extends [`ServiceResponse`](../interfaces/corelib_q.ServiceResponse.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | [`ServiceOptions`](../interfaces/corelib_q.ServiceOptions.md)<`TResponse`\> |

#### Returns

`JQueryXHR`

#### Defined in

[src/q/services.ts:28](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/services.ts#L28)

___

### serviceRequest

▸ **serviceRequest**<`TResponse`\>(`service`, `request?`, `onSuccess?`, `options?`): `JQueryXHR`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TResponse` | extends [`ServiceResponse`](../interfaces/corelib_q.ServiceResponse.md) |

#### Parameters

| Name | Type |
| :------ | :------ |
| `service` | `string` |
| `request?` | `any` |
| `onSuccess?` | (`response`: `TResponse`) => `void` |
| `options?` | [`ServiceOptions`](../interfaces/corelib_q.ServiceOptions.md)<`TResponse`\> |

#### Returns

`JQueryXHR`

#### Defined in

[src/q/services.ts:124](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/services.ts#L124)

___

### setEquality

▸ **setEquality**(`request`, `field`, `value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`ListRequest`](../interfaces/corelib_q.ListRequest.md) |
| `field` | `string` |
| `value` | `any` |

#### Returns

`void`

#### Defined in

[src/q/services.ts:133](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/services.ts#L133)

___

### setTypeNameProp

▸ **setTypeNameProp**(`type`, `value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `type` | [`Type`](corelib_q.md#type) |
| `value` | `string` |

#### Returns

`void`

#### Defined in

[src/q/system.ts:142](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L142)

___

### single

▸ **single**<`TItem`\>(`array`, `predicate`): `TItem`

Gets first element in an array that matches given predicate.
Throws an error if no matches is found, or there are multiple matches.

**`Example`**

```ts
first([1, 2, 3], x => x == 2); // 2
first([1, 2, 3], x => x == 4); // throws error.
```

#### Type parameters

| Name |
| :------ |
| `TItem` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `array` | `TItem`[] | Array to test. |
| `predicate` | (`x`: `TItem`) => `boolean` | Predicate to test elements. |

#### Returns

`TItem`

First element that matches.

#### Defined in

[src/q/arrays.ts:151](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/arrays.ts#L151)

___

### splitDateString

▸ **splitDateString**(`s`): `string`[]

Splits a date string into an array of strings, each containing a single date part.
It can handle separators "/", ".", "-" and "\".

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `s` | `string` | The string to split. |

#### Returns

`string`[]

#### Defined in

[src/q/formatting.ts:1038](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L1038)

___

### startsWith

▸ **startsWith**(`s`, `prefix`): `boolean`

Checks if the string starts with the prefix

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `s` | `string` | String to check. |
| `prefix` | `string` | Prefix to check. |

#### Returns

`boolean`

True if the string starts with the prefix.

#### Defined in

[src/q/strings.ts:51](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/strings.ts#L51)

___

### success

▸ **success**(`message`, `onOk?`, `options?`): `void`

**`Obsolete`**

use successDialog

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `onOk?` | () => `void` |
| `options?` | [`ConfirmOptions`](../interfaces/corelib_q.ConfirmOptions.md) |

#### Returns

`void`

#### Defined in

[src/q/dialogs.ts:556](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L556)

___

### successDialog

▸ **successDialog**(`message`, `onOk?`, `options?`): `void`

Display a success dialog

**`See`**

ConfirmOptions

**`Example`**

```ts
successDialog("Operation complete", () => { 
    // do something when OK is clicked
}
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `message` | `string` | The message to display |
| `onOk?` | () => `void` | Callback for OK button click |
| `options?` | [`ConfirmOptions`](../interfaces/corelib_q.ConfirmOptions.md) | Additional options. |

#### Returns

`void`

#### Defined in

[src/q/dialogs.ts:556](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L556)

___

### text

▸ **text**(`key`): `string`

**`Obsolete`**

prefer localText for better discoverability

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`string`

#### Defined in

[src/q/localtext.ts:4](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/localtext.ts#L4)

___

### toGrouping

▸ **toGrouping**<`TItem`\>(`items`, `getKey`): [`Grouping`](corelib_q.md#grouping)<`TItem`\>

Maps an array into a dictionary with keys determined by specified getKey() callback,
and values that are arrays containing elements for a particular key.

**`Example`**

```ts
toGrouping([1, 2, 3], x => x % 2 == 0 ? "even" : "odd"); // { odd: [1, 3], even: [2] }
```

#### Type parameters

| Name |
| :------ |
| `TItem` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `items` | `TItem`[] | Array to map. |
| `getKey` | (`x`: `TItem`) => `any` | Function that returns key for each item. |

#### Returns

[`Grouping`](corelib_q.md#grouping)<`TItem`\>

Grouping object.

#### Defined in

[src/q/arrays.ts:180](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/arrays.ts#L180)

___

### toId

▸ **toId**(`id`): `any`

Converts a string to an ID. If the string is a number, it is returned as-is.
If the string is empty, null or whitespace, null is returned.
Otherwise, it is converted to a number if possible. If the string is not a
valid number or longer than 14 digits, the trimmed string is returned as-is.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `id` | `any` | the string to convert to an ID |

#### Returns

`any`

#### Defined in

[src/q/formatting.ts:628](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L628)

___

### toSingleLine

▸ **toSingleLine**(`str`): `string`

Converts the string to single line by removing line end characters

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `str` | `string` | String to convert. |

#### Returns

`string`

#### Defined in

[src/q/strings.ts:59](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/strings.ts#L59)

___

### today

▸ **today**(): `Date`

#### Returns

`Date`

#### Defined in

[src/q/system.ts:11](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/system.ts#L11)

___

### toggleClass

▸ **toggleClass**(`el`, `cls`, `remove?`): `void`

Toggles the class on the element handling spaces like jQuery addClass does.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `el` | `Element` | the element |
| `cls` | `string` | the class to toggle |
| `remove?` | `boolean` | if true, the class will be added, if false the class will be removed, otherwise it will be toggled. |

#### Returns

`void`

#### Defined in

[src/q/html.ts:132](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/html.ts#L132)

___

### triggerLayoutOnShow

▸ **triggerLayoutOnShow**(`element`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `element` | `JQuery` |

#### Returns

`void`

#### Defined in

[src/q/layout.ts:93](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/layout.ts#L93)

___

### trim

▸ **trim**(`s`): `string`

Trims the whitespace characters from the start and end of the string
This returns empty string even when the string is null or undefined.

#### Parameters

| Name | Type |
| :------ | :------ |
| `s` | `string` |

#### Returns

`string`

#### Defined in

[src/q/strings.ts:81](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/strings.ts#L81)

___

### trimEnd

▸ **trimEnd**(`s`): `any`

Trims the whitespace characters from the end of the string

#### Parameters

| Name | Type |
| :------ | :------ |
| `s` | `string` |

#### Returns

`any`

#### Defined in

[src/q/strings.ts:66](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/strings.ts#L66)

___

### trimStart

▸ **trimStart**(`s`): `any`

Trims the whitespace characters from the start of the string

#### Parameters

| Name | Type |
| :------ | :------ |
| `s` | `string` |

#### Returns

`any`

#### Defined in

[src/q/strings.ts:73](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/strings.ts#L73)

___

### trimToEmpty

▸ **trimToEmpty**(`s`): `string`

Trims the whitespace characters from the start and end of the string
Returns empty string if the string is null or undefined.

#### Parameters

| Name | Type |
| :------ | :------ |
| `s` | `string` |

#### Returns

`string`

#### Defined in

[src/q/strings.ts:89](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/strings.ts#L89)

___

### trimToNull

▸ **trimToNull**(`s`): `string`

Trims the whitespace characters from the start and end of the string
Returns null if the string is null, undefined or whitespace.

#### Parameters

| Name | Type |
| :------ | :------ |
| `s` | `string` |

#### Returns

`string`

#### Defined in

[src/q/strings.ts:97](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/strings.ts#L97)

___

### trunc

▸ **trunc**(`n`): `number`

Truncates a number to an integer number.

#### Parameters

| Name | Type |
| :------ | :------ |
| `n` | `number` |

#### Returns

`number`

#### Defined in

[src/q/formatting.ts:309](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L309)

___

### tryFirst

▸ **tryFirst**<`TItem`\>(`array`, `predicate`): `TItem`

Gets first element in an array that matches given predicate (similar to LINQ's FirstOrDefault).
Returns null if no match is found.

**`Example`**

```ts
tryFirst([1, 2, 3], x => x == 2); // 2
tryFirst([1, 2, 3], x => x == 4); // null
```

#### Type parameters

| Name |
| :------ |
| `TItem` |

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `array` | `TItem`[] | Array to test. |
| `predicate` | (`x`: `TItem`) => `boolean` | Predicate to test elements. |

#### Returns

`TItem`

First element that matches.

#### Defined in

[src/q/arrays.ts:204](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/arrays.ts#L204)

___

### tryGetText

▸ **tryGetText**(`key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `key` | `string` |

#### Returns

`string`

#### Defined in

[src/q/localtext.ts:52](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/localtext.ts#L52)

___

### turkishLocaleCompare

▸ **turkishLocaleCompare**(`a`, `b`): `number`

This is an alias for Culture.stringCompare, left in for compatibility reasons.

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `string` |
| `b` | `string` |

#### Returns

`number`

#### Defined in

[src/q/formatting.ts:58](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L58)

___

### turkishLocaleToLower

▸ **turkishLocaleToLower**(`a`): `string`

A string to lowercase function that handles special Turkish
characters like 'ı'. Left in for compatibility reasons.

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `string` |

#### Returns

`string`

#### Defined in

[src/q/formatting.ts:170](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L170)

___

### turkishLocaleToUpper

▸ **turkishLocaleToUpper**(`a`): `string`

A string to uppercase function that handles special Turkish
characters like 'ı'. Left in for compatibility reasons.

#### Parameters

| Name | Type |
| :------ | :------ |
| `a` | `string` |

#### Returns

`string`

#### Defined in

[src/q/formatting.ts:180](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/formatting.ts#L180)

___

### validateForm

▸ **validateForm**(`form`, `opt`): `JQueryValidation.Validator`

#### Parameters

| Name | Type |
| :------ | :------ |
| `form` | `JQuery` |
| `opt` | `ValidationOptions` |

#### Returns

`JQueryValidation.Validator`

#### Defined in

[src/q/validation.ts:230](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/validation.ts#L230)

___

### validateOptions

▸ **validateOptions**(`options?`): `ValidationOptions`

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `ValidationOptions` |

#### Returns

`ValidationOptions`

#### Defined in

[src/q/validateoptions.ts:61](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/validateoptions.ts#L61)

___

### validatorAbortHandler

▸ **validatorAbortHandler**(`validator`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `validator` | `any` |

#### Returns

`void`

#### Defined in

[src/q/validateoptions.ts:54](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/validateoptions.ts#L54)

___

### warning

▸ **warning**(`message`, `options?`): `void`

**`Obsolete`**

use warningDialog

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `string` |
| `options?` | [`AlertOptions`](../interfaces/corelib_q.AlertOptions.md) |

#### Returns

`void`

#### Defined in

[src/q/dialogs.ts:584](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L584)

___

### warningDialog

▸ **warningDialog**(`message`, `options?`): `void`

Display a warning dialog

**`See`**

AlertOptions

**`Example`**

```ts
warningDialog("Something is odd!");
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `message` | `string` | The message to display |
| `options?` | [`AlertOptions`](../interfaces/corelib_q.AlertOptions.md) | Additional options. |

#### Returns

`void`

#### Defined in

[src/q/dialogs.ts:584](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/dialogs.ts#L584)

___

### zeroPad

▸ **zeroPad**(`n`, `len`): `string`

Pads the start of string to make it the specified length.

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `n` | `number` | - |
| `len` | `number` | Target length of the string. |

#### Returns

`string`

#### Defined in

[src/q/strings.ts:121](https://github.com/serenity-is/serenity/blob/master/packages/corelib/src/q/strings.ts#L121)