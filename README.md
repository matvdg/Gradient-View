# Gradient-View
A Swift 3 UIView class with a gradient customizable in the storyboard (colors, direction, shadows, cornerRadius...)

GradientView: UIView is a @IBDesignable class so that it's rendered in your storyboard, and all its properties are @IBInspectable so that you can customize your gradient view inside the storyboard in the Attributes inspector.

# Quick install:
* Just drag this class into your project
* In your storyboard, select a UIView
* Go the the identity inspector and in the class field, type GradientView instead of UIView
* Play with the attributes inspector with real-times results!
  * you can select two colors for the gradient
  * and one color for the shadow
  * you can choose the shadow position (x/y) and its blur
  * the direction of the gradient (top left is 0,0 and bottom right is 1,1) from the start point to the end point
  * the corner radius of your view

![Image of Gradient View](https://raw.githubusercontent.com/matvdg/Gradient-View/master/example.png)
