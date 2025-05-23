# ConnectorState.Connecting Class  
  
**Namespace:** Nodify.Interactivity  
  
**Assembly:** Nodify  
  
**Inheritance:** [Object](https://docs.microsoft.com/en-us/dotnet/api/System.Object) → [InputElementState\<Connector\>](Nodify_Interactivity_InputElementState_TElement_) → [DragState\<Connector\>](Nodify_Interactivity_DragState_TElement_) → [ConnectorState.Connecting](Nodify_Interactivity_ConnectorState_Connecting)  
  
**References:** [Connector](Nodify_Connector)  
  
```csharp  
public class Connecting : DragState<Connector>  
```  
  
## Constructors  
  
### ConnectorState.Connecting(Connector)  
  
```csharp  
public Connecting(Connector connector);  
```  
  
**Parameters**  
  
`connector` [Connector](Nodify_Connector)  
  
## Properties  
  
### CanCancel  
  
```csharp  
protected override bool CanCancel { get; set; }  
```  
  
**Property Value**  
  
[Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean)  
  
### HasContextMenu  
  
```csharp  
protected override bool HasContextMenu { get; set; }  
```  
  
**Property Value**  
  
[Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean)  
  
### IsToggle  
  
```csharp  
protected override bool IsToggle { get; set; }  
```  
  
**Property Value**  
  
[Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean)  
  
## Methods  
  
### OnBegin(InputEventArgs)  
  
```csharp  
protected override void OnBegin(InputEventArgs e);  
```  
  
**Parameters**  
  
`e` [InputEventArgs](https://docs.microsoft.com/en-us/dotnet/api/System.Windows.Input.InputEventArgs)  
  
### OnCancel(InputEventArgs)  
  
```csharp  
protected override void OnCancel(InputEventArgs e);  
```  
  
**Parameters**  
  
`e` [InputEventArgs](https://docs.microsoft.com/en-us/dotnet/api/System.Windows.Input.InputEventArgs)  
  
### OnEnd(InputEventArgs)  
  
```csharp  
protected override void OnEnd(InputEventArgs e);  
```  
  
**Parameters**  
  
`e` [InputEventArgs](https://docs.microsoft.com/en-us/dotnet/api/System.Windows.Input.InputEventArgs)  
  
### OnMouseMove(MouseEventArgs)  
  
```csharp  
protected override void OnMouseMove(MouseEventArgs e);  
```  
  
**Parameters**  
  
`e` [MouseEventArgs](https://docs.microsoft.com/en-us/dotnet/api/System.Windows.Input.MouseEventArgs)  
  
