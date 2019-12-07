# Initial page

{% page-ref page="group1/haushaltsplan.md" %}

{% page-ref page="./" %}

> > ```text
> > Private Sub TextBox2_KeyPress(ByVal sender As System.Object, ByVal e As System.Windows.Forms.KeyPressEventArgs) Handles TextBox1.KeyPress
> >     If e.KeyChar = Convert.ToChar(1) Then
> >         DirectCast(sender, TextBox).SelectAll()
> >         e.Handled = True
> >     End If
> > End Sub
> >
> > Private Sub Button3_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles Button3.Click
> >     TextBox1.Clear()
> >     TextBox1.Text = Clipboard.GetText
> > End Sub
> >
> > Private Sub Form1_Load(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles MyBase.Load
> >
> > End Sub
> > ```

## paragraph1

## Heading1

* list 1
* list 2
* list 3



1. list 1
2. list 2
3. list 3

* [ ] check1
* [ ] check2

{% tabs %}
{% tab title="First Tab" %}
## haed1-1
{% endtab %}

{% tab title="Second Tab" %}
## Head1-2
{% endtab %}
{% endtabs %}

{% hint style="success" %}
hint
{% endhint %}

{% page-ref page="./" %}

{% file src=".gitbook/assets/haushaltsplan\_kapitel2.docx" caption="download" %}

