# JSONSchema-react-native-form
A React-Native component for building forms based on the JSON Schema.

## Story behind the component
The React-Native component is built in order to consumed by Graft(ASPS) app. Graft has requirements of showing two lengthy forms, We decided to utilize JSONSchema to render forms. Ideally, this component should support all the forms constructed in this organization. It may not support some of standard or complex jsonSchema as it is still in development mode and was build mainly focusing on Graft app. The code has few additional features which lie beyond the JSON schema universe to meet the requirements of Graft app. 

## Accomplishments
 - renders the form with schema, uiSchema & formData
 - uniform styling of the components
 - Supported components see list below
 - ajv validation implented for errors
 - on Submit form if error then form gets scrolled to the topmost error in the form.


## Roadmap
 - Support for structured & complex JSON schema includes $id, $ref, definitions, additional properties
 - Support for defaults
 - Better ajv error formulation for readable & understandable errors
 - Support for theme provider for the form components
 - Prop type declarations for all components
 
 
## Component list
[*Calculated](https://js.do/code/314698)


| boolean | | 
| ------ | ------ | 
| checkbox| CheckboxWidget| 
| radio| RadioWidget| 
| select| UnsupportedWidget| 
| hidden| UnsupportedWidget| 
| text| CheckboxWidget| 


| string | | 
| ------ | ------ | 
| text| TextWidget| 
| password| UnsupportedWidget| 
| email| UnsupportedWidget| 
| hostname| TextWidget| 
| ipv4| TextWidget| 
| ipv6| TextWidget| 
| uri| UnsupportedWidget| 
| data-url| UnsupportedWidget| 
| radio| RadioWidget| 
| select| DropDownWidget| 
| textarea| UnsupportedWidget| 
| hidden| UnsupportedWidget| 
| date| DateWidget| 
| datetime| UnsupportedWidget| 
| date-time| UnsupportedWidget| 
| alt-date| UnsupportedWidget| 
| alt-datetime| UnsupportedWidget| 
| color| UnsupportedWidget| 
| file| UnsupportedWidget| 


| number | | 
| ------ | ------ | 
| text| TextWidget| 
| select| UnsupportedWidget| 
| updown| UnsupportedWidget| 
| range| UnsupportedWidget| 
| radio| RadioWidget| 
| hidden| UnsupportedWidget| 


| integer | | 
| ------ | ------ | 
| text| TextWidget| 
| select| DropDownWidget| 
| updown| UnsupportedWidget| 
| range| SliderWidget| 
| radio| RadioWidget| 
| hidden| UnsupportedWidget| 
| checkboxes| CheckboxesWidget| 


| array | | 
| ------ | ------ | 
| select| UnsupportedWidget| 
| checkboxes| CheckboxesWidget| 
| files| UnsupportedWidget| 