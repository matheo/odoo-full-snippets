
# odoo-full-snippets

Atom snippets for Odoo following the [Official Guidelines](http://www.odoo.com/documentation/9.0/reference/guidelines.html),
aiming to be a complete tool for agile development with Odoo v10+. The snippets are built to produce from the most basic result
to the most complex one, giving the option to supress not required options and adding removable comments too.


## Available snippets

### XML

#### xml-views
* `ooxml` Setup the main odoo xml tags.
* `oodata` Setup the xml for not-updatable data.
* `ootree` Create tree view.
* `ootreeinherit` Inherit tree view.
* `oosearch` Create search view.
* `oosearchinherit` Inherit search view.
* `ooform` Create form view.
* `ooforminherit` Inherit form view.
* `ooformheader` Generate a form header with state and buttons.
* `oogrid` Add nested groups.
* `ootabs` Add notebook and a page.
* `oopage` Add page.

#### xml-records
* `ooaction` Create new window action.
* `ooactionview` Create new action view.
* `ooactwindow` Create new act_window.
* `ooserveraction` Create new server action.
* `ooclientaction` Create new client action.
* `oomenuroot` Create a top menu item.
* `oomenucategory` Create a menu item for category.
* `oomenuaction` Create a menu item for actions.
* `oocategory` Create security category.
* `oogroup` Create group.
* `oorule` Create security rule.
* `ooworkflow` Create workflow.
* `ooactivity` Add activity to workflow.
* `ootransition` Add transition to workflow.
* `oowizardaction` Create new wizard action.
* `oowizardview` Create new wizard view.
* `oosequence` Register sequence.

#### xml-utils
* `oodomain` Generate a domain dictionary.
* `oodomainadv` Generate an advanced domain.
* `oocontext` Generate a context dictionary.
* `oocontextadv` Generate an advanced context.
* `oofield` Generate a field tag.
* `oochatter` Chatter: social messaging and followers.
* `oofiltertoday` Filter: Today

## PYTHON

#### py-model
* `oomodel` Create Odoo Model.
* `oomodelinherit` Inherit Odoo Model.
* `ooffield` Full Field.
* `oofchar` Char Field.
* `oofboolean` Boolean Field.
* `oofinteger` Integer Field.
* `ooffloat` Float Field.
* `ooftext` Text Field.
* `oofhtml` HTML Field.
* `oofdate` Date Field.
* `oofdatetime` DateTime Field.
* `oofbinary` Binary Field.
* `oofselection` Selection Field.
* `oofseladd` Selection Addition.
* `oofreference` Reference Field.
* `oofmany2one` Many2one Field.
* `oofone2many` One2many Field.
* `oofmany2many` Many2many Field.
* `oofcompute` Compute Field.
* `oomcompute` Compute Method.
* `oomconstrains` Constrains Method.
* `oomonchange` Onchange Method.
* `oomaction` Action Method.

#### py-orm
* `oopids` RecordSet ids.
* `oopensureone` RecordSet Ensure One.
* `oopexists` RecordSet Exists Check -> records.
* `oopfiltered` RecordSet Filtered.
* `oopsorted` RecordSet Sorted.
* `oopmapped` RecordSet Mapped.
* `oormcreate` RecordSet Create -> record.
* `oormbrowse` RecordSet Browse -> records.
* `oormunlink` RecordSet Unlink / Delete.
* `oormwrite` RecordSet Write.
* `oormreadgroup` RecordSet Read Group.
* `oormsearch` RecordSet Search.
* `oormcount` RecordSet Search Count -> int.
* `oormnamesearch` RecordSet Name Search -> records.

#### py-utils
* `oopy` Python File Header.
* `oodatectxtoday` fields.Date.context_today(record, timestamp=None) -> str
* `oodatetimestamp` fields.Datetime.context_timestamp(record, timestamp=None) -> datetime
* `oodatefromstring` fields.Date[time].from_string(value) -> date[time]
* `oodatetostring` fields.Date[time].to_string(value) -> str
* `oodatetoday` fields.Date.today(*args) -> str
* `oodatenow` fields.Datetime.now(*args) -> str

### CSV

* `ooaccess` model.access.csv
* `ooaccessrow` model.access.csv row


## Contributing

Any help is welcome.
Please create [new issues](https://github.com/matheo/odoo-full-snippets/issues/new) to submit suggestions
and create [pull requests](https://github.com/matheo/odoo-full-snippets/compare) for improvements.

This package is based in [odoo-snippets by nicolasmartinelli](https://github.com/nicolasmartinelli/atom-odoo-snippets).
