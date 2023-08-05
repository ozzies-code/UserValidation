# UserValidation
In this application it is required to validate the social security number of a person that must match their access PIN according to the format established in an input mask. if the format does not match it will result in an error message. 

VBasic: 
Public Class FormValUsu

    Private Sub btnRegistrarse_Click(ByVal sender As System.Object, ByVal e As System.EventArgs) Handles btnRegistrarse.Click

        If MaskedTextBox1.Text = "555-55-1212" And MaskedTextBox2.Text = "54321" Then

            MsgBox("!Bienvenido al Sistema¡")
        Else
            MsgBox("Numero Irreconocible")
        End If

    End Sub
End Class
