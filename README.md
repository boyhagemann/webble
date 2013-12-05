Webble CMS
==========


## Packages

#### Form
Contains a form builder with a fluent interface. 
You can register new and custom elements with their own view.

#### Model
Build migration files and generates model classes.

#### Overview
Present data in a list view. 
Uses both Form and Model to render the data.

#### Crud
Provides a CrudController with all CRUD methods.
It uses Form, Overview and Model to manage your model data.

#### Pages
Converts a standard Route into a Page. 
The page has a layout, title and metadata.
Pages can be the base building block on which the CMS flourishes.

#### Content
Display multiple content blocks on a single page.
You can have each content block dispatch a separate controller action with their own view.

#### Navigation
Offers tree based navigation nodes. 
The package offers standard Menu and other view types.

#### Admin
Covers the basic admin interface. Also holds the Resource model.
This model is used to manage dynamic content in your application.

#### Text
This is a simple content block that provides a wysiwyg text editor.

#### User
Provides user management including user groups and permissions.
It has a build in auth system.


## Subscribers
Subscribers are a set of one or more event listeners.
The combination of these events solve a common problem or improves your workflow.
It is the glue that binds the packages together.

Each package can provide a set of helpful subscribers.
If you use just one package, you can register these subscribers to your application.
