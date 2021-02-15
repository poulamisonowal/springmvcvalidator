# springmvcvalidator
This example is to apply validation in forms using spring validations. We will use hibernate validator
Hibernate validator can be used to validate data, which is a very important issue in every layer of an application. For example, validating is important when submitting HTML forms. Hibernate validator framework provides many annotations, that can be used to validate input fields of a form against constraints.
Constraints used 
@Size : This annotation is used to set the size of the field. It has three properties to configure, the min, max and the message to be set. 
@Min : This annotation is used to set the min size of a field
@NotNull : With this annotation you can make sure that the field has a value.
@Length : This annotation is similar to @Size.
@Pattern : This annotation can be used when we want to chack a field against a regular expression. The regex is set as an attribute to the annotation.
@Range : This annotation can be used to set a range of min and max values to a field.
