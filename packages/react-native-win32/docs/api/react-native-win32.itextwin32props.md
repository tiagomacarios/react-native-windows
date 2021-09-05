<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@office-iss/react-native-win32](./react-native-win32.md) &gt; [ITextWin32Props](./react-native-win32.itextwin32props.md)

## ITextWin32Props interface

<b>Signature:</b>

```typescript
export interface ITextWin32Props extends Omit<RN.TextProps, TextWin32OmitTypes>, BasePropsWin32 
```
<b>Extends:</b> Omit&lt;RN.TextProps, [TextWin32OmitTypes](./react-native-win32.textwin32omittypes.md)<!-- -->&gt;, [BasePropsWin32](./react-native-win32.basepropswin32.md)

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [focusable](./react-native-win32.itextwin32props.focusable.md) | boolean | Enables a focusable label with copyability but without character selectability (property:selectable) |
|  [keyDownEvents](./react-native-win32.itextwin32props.keydownevents.md) | [IHandledKeyboardEvent](./react-native-win32.ihandledkeyboardevent.md)<!-- -->\[\] |  |
|  [keyUpEvents](./react-native-win32.itextwin32props.keyupevents.md) | [IHandledKeyboardEvent](./react-native-win32.ihandledkeyboardevent.md)<!-- -->\[\] |  |
|  [onBlur](./react-native-win32.itextwin32props.onblur.md) | (ev: RN.NativeSyntheticEvent&lt;{}&gt;) =&gt; void | The onBlur event occurs when an element loses focus. The opposite of onBlur is onFocus. Note that in React Native, unlike in the web, the onBlur event bubbles (similar to onFocusOut in the web).<code>ev.target === ev.currentTarget</code> when the focus is being lost from this component. <code>ev.target !== ev.currentTarget</code> when the focus is being lost from a descendant. |
|  [onBlurCapture](./react-native-win32.itextwin32props.onblurcapture.md) | (ev: RN.NativeSyntheticEvent&lt;{}&gt;) =&gt; void | The onBlur event occurs when an element loses focus. The opposite of onBlur is onFocus. Note that in React Native, unlike in the web, the onBlur event bubbles (similar to onFocusOut in the web).<code>ev.target === ev.currentTarget</code> when the focus is being lost from this component. <code>ev.target !== ev.currentTarget</code> when the focus is being lost from a descendant. |
|  [onFocus](./react-native-win32.itextwin32props.onfocus.md) | (ev: RN.NativeSyntheticEvent&lt;{}&gt;) =&gt; void | The onFocus event occurs when an element gets focus. The opposite of onFocus is onBlur. Note that in React Native, unlike in the web, the onFocus event bubbles (similar to onFocusIn in the web).<code>ev.target === ev.currentTarget</code> when the focus is being lost from this component. <code>ev.target !== ev.currentTarget</code> when the focus is being lost from a descendant. |
|  [onFocusCapture](./react-native-win32.itextwin32props.onfocuscapture.md) | (ev: RN.NativeSyntheticEvent&lt;{}&gt;) =&gt; void | The onFocus event occurs when an element gets focus. The opposite of onFocus is onBlur. Note that in React Native, unlike in the web, the onFocus event bubbles (similar to onFocusIn in the web).<code>ev.target === ev.currentTarget</code> when the focus is being lost from this component. <code>ev.target !== ev.currentTarget</code> when the focus is being lost from a descendant. |
|  [onKeyDown](./react-native-win32.itextwin32props.onkeydown.md) | (args: [IKeyboardEvent](./react-native-win32.ikeyboardevent.md)<!-- -->) =&gt; void |  |
|  [onKeyDownCapture](./react-native-win32.itextwin32props.onkeydowncapture.md) | (args: [IKeyboardEvent](./react-native-win32.ikeyboardevent.md)<!-- -->) =&gt; void |  |
|  [onKeyUp](./react-native-win32.itextwin32props.onkeyup.md) | (args: [IKeyboardEvent](./react-native-win32.ikeyboardevent.md)<!-- -->) =&gt; void |  |
|  [onKeyUpCapture](./react-native-win32.itextwin32props.onkeyupcapture.md) | (args: [IKeyboardEvent](./react-native-win32.ikeyboardevent.md)<!-- -->) =&gt; void |  |
|  [textStyle](./react-native-win32.itextwin32props.textstyle.md) | [TextStyle](./react-native-win32.textstyle.md) | Role-based styling of the text control. The styles applied include font face, size, weight and color. These styles take precedence over the <code>style</code> property. |
|  [tooltip](./react-native-win32.itextwin32props.tooltip.md) | string | Tooltip displayed on mouse hover of this element |
