> **iOS Renderer:**

    Xamarin.Forms.Platform.iOS.ViewRenderer<TView, TNavitveView>
    Platform Specific Control: types deriving from MonoTouch.UIKit.UIView

> **Android Renderer:**

    Xamarin.Forms.Platform.Android.ViewRenderer<TView, TNavitveView>
    Platform Specific Control: types deriving from Android.Views.ViewGroup
> 
> **Windows Phone Renderer:** 

    Xamarin.Forms.Platform.WinPhone.ViewRenderer<TElement, TNativeElement>
    Platform Specific Control: types deriving from System.Windows.FrameworkElement

> # Layout Renderers #

> **ContentPage**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.PageRenderer
    Platform Specific Control: MonoTouch.UIKit.UIView
> Android Renderer:

    Xamarin.Forms.Platform.Android.PageRenderer
    Platform Specific Control: Android.Views.ViewGroup
> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.PageRenderer
    Platform Specific Control: System.Windows.Controls.Panel

> **MasterDetailPage**
> 
iOS Renderer:

    Xamarin.Forms.Platform.iOS.PhoneMasterDetailRenderer for iPhone
	Xamarin.Forms.Platform.iOS.TabletMasterDetailRenderer for iPad
    Platform Specific Control: custom flyout on iPhone
	MonoTouch.UIKit.UISplitViewController for iPad
> Android Renderer:

    Xamarin.Forms.Platform.Android.MasterDetailRenderer
    Platform Specific Control: Android.Support.V4.Widget.DrawerLayout

> Windows Phone

    Renderer: Xamarin.Forms.Platform.WinPhone.MasterDetailRenderer
    Platform Specific Control: System.Windows.Controls.Panel

> **NavigationPage**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.NavigationRenderer
    Platform Specific Control: MonoTouch.UIKit.UIToolbar and
	derives from MonoTouch.UIKit.UINavigationController
> Android Renderer:

    Xamarin.Forms.Platform.Android.NavigationRenderer
    Platform Specific Control: No View of its own, deals with switching
	content derived from Android.Views.View
> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.NavigationPageRenderer
    Platform Specific Control: No View of its own, deals with switching
	content derived from System.Windows.FrameworkElements

> **TabbedPage**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.TabbedRenderer
    Platform Specific Control: MonoTouch.UIKit.UIViewController
	with contained MonoTouch.UIKit.UIView

> Android Renderer:

    Xamarin.Forms.Platform.Android.TabbedRenderer
    Platform Specific Control: No View of its own, deals with switching
	content derived from Android.Views.View

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.TabbedPageRenderer
    Platform Specific Control: inherits from Microsoft.Phone.Controls.Pivot

> **CarouselPage**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.CarouselPageRenderer
    Platform Specific Control: MonoTouch.UIKit.UIScrollView
> Android Renderer:

	Xamarin.Forms.Platform.Android.CarouselPageRenderer
    Platform Specific Control: Android.Views.View
> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.CarouselPageRenderer
    Platform Specific Control: Microsoft.Phone.Controls.PanoramaItem

> **Frame**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.FrameRenderer
    Platform Specific Control: MonoTouch.UIKit.UIView
> Android Renderer:

    Xamarin.Forms.Platform.Android.FrameRenderer
    Platform Specific Control: Android.Graphics.Drawables.Drawable

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.FrameRenderer
    Platform Specific Control: System.Windows.UIElement

> **ScrollView**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.ScrollViewRenderer
    Platform Specific Control: MonoTouch.UIKit.UIScrollView
> Android Renderer:

    Xamarin.Forms.Platform.Android.ScrollViewRenderer
    Platform Specific Control: Android.Widget.ScrollView
> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.ScrollViewRenderer
    Platform Specific Control: System.Windows.Controls.ScrollViewer


> **TableView **
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.TableViewRenderer
    Platform Specific Control: MonoTouch.UIKit.UITableView

> Android Renderer:
    
    Xamarin.Forms.Platform.Android.TableViewRenderer (Table),
	Xamarin.Forms.Platform.Android.TableViewModelRenderer (Rows)
	Platform Specific Control: Android.Widget.ListView (Table), Android.Views.View (Row)
> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.TableViewRenderer
    Platform Specific Control: Microsoft.Phone.Controls.LongListSelector

# Control Renderers #
> **ActivityIndicator** 
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.ActivityIndicatorRenderer
    Platform Specific Control: MonoTouch.UIKit.UIActivityIndicatorView

> Android Renderer:

    Xamarin.Forms.Platform.Android.ActivityIndicatorRenderer
    Platform Specific Control: Android.Widget.ProgressBar

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.ActivityIndicatorRenderer
    Platform Specific Control: System.Windows.Controls.ProgressBar

> **BoxView** 
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.BoxRenderer
    Platform Specific Control: MonoTouch.CoreGrahics.CGContext

> Android Renderer:

    Xamarin.Forms.Platform.Android.BoxRenderer
    Platform Specific Control: Android.Views.ViewGroup

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.BoxViewRenderer
    Platform Specific Control: System.Windows.Shapes.Rectangle

> **Button**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.ButtonRenderer
    Platform Specific Control: MonoTouch.UIKit.UIButton

> Android Renderer:

    Xamarin.Forms.Platform.Android.ButtonRenderer
    Platform Specific Control: Android.Widget.Button

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.ButtonRenderer
    Platform Specific Control: System.Windows.Controls.Button

> **DatePicker**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.DatePickerRenderer
    Platform Specific Control: MonoTouch.UIKit.UIToolbar with 
	MonoTouch.UIKit.UIBarButtonItems

> Android Renderer:

    Xamarin.Forms.Platform.Android.DatePickerRenderer
    Platform Specific Control: Android.App.DatePickerDialog

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.DatePickerRenderer
    Platform Specific Control: Microsoft.Phone.Controls.DateTimePickerBase

> **Editor**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.EditorRenderer
    Platform Specific Control: MonoTouch.UIKit.UITextView

> Android Renderer:

    Xamarin.Forms.Platform.Android.EditorRenderer
    Platform Specific Control: Android.Widget.EditText

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.EditorRenderer
    Platform Specific Control: System.Windows.Controls.TextBox

> **Entry**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.EntryRenderer
    Platform Specific Control: MonoTouch.UIKit.UITextField

> Android Renderer:

    Xamarin.Forms.Platform.Android.EntryRenderer
    Platform Specific Control: Android.Widget.EditText

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.EntryRenderer
    Platform Specific Control: Microsoft.Phone.Controls.PhoneTextBox
	or System.Windows.Controls.PasswordBox

> **Image**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.ImageRenderer
    Platform Specific Control: MonoTouch.UIKit.UIImageView

> Android Renderer:

    Xamarin.Forms.Platform.Android.ImageRenderer
    Platform Specific Control: Android.Widget.ImageView

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.ImageRenderer
    Platform Specific Control: System.Windows.Controls.Image

> **Label**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.LabelRenderer
    Platform Specific Control: MonoTouch.UIKit.UILabel

> Android Renderer:

    Xamarin.Forms.Platform.Android.LabelRenderer
    Platform Specific Control: Android.Widget.TextView

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.LabelRenderer
    Platform Specific Control: System.Windows.Controls.TextBlock

> **ListView**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.ListViewRenderer
    Platform Specific Control: MonoTouch.UIKit.UITableView

> Android Renderer:

    Xamarin.Forms.Platform.Android.ListViewRenderer
	(currently internal in scope and not derivable)
    Platform Specific Control: Android.Widget.ListView

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.ListViewRenderer
    Platform Specific Control: Microsoft.Phone.Controls.LongListSelector

> **OpenGLView**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.OpenGLViewRenderer
    Platform Specific Control: MonoTouch.GLKit.GLKView
> Android Renderer:
    
    Xamarin.Forms.Platform.Android.OpenGLRenderer
	(currently internal in scope and not derivable)
    Platform Specific Control: Android.Opengl.GLSurfaceView

> **Picker**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.PickerRenderer
    Platform Specific Control: MonoTouch.UIKit.UIPickerView, 
	MonoTouch.UIKit.UIPickerViewModel, MonoTouch.UIKit.UIToolBar,
	Two MonoTouch.UIKit.UIBarButtonItems, MonoTouch.UIKit.UITextField

> Android Renderer:

    Xamarin.Forms.Platform.Android.PickerRenderer
    Platform Specific Control: Android.Widget.TextView,
	Android.App.AlertDialog and Android.Widget.NumberPicker

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.PickerRenderer
    Platform Specific Control: Microsoft.Phone.Controls.ListPicker

> **ProgressBar**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.ProgressBarRenderer
    Platform Specific Control: MonoTouch.UIKit.UIProgressView

> Android Renderer:

    Xamarin.Forms.Platform.Android.ProgressBarRenderer
    Platform Specific Control: Android.Widget.ProgressBar

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.ProgressBarRenderer
    Platform Specific Control: System.Windows.Controls.ProgressBar

> **SearchBar**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.SearchBarRenderer
    Platform Specific Control: MonoTouch.UIKit.UISearchBar

> Android Renderer:

    Xamarin.Forms.Platform.Android.SearchBarRenderer
    Platform Specific Control: Android.Widget.SearchView

> Windows Phone Renderer:
    
    Xamarin.Forms.Platform.WinPhone.SearchBarRenderer
    Platform Specific Control: Microsoft.Phone.Controls.PhoneTextBox

> **Slider**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.SliderRenderer
    Platform Specific Control: MonoTouch.UIKit.UISlider

> Android Renderer:

    Xamarin.Forms.Platform.Android.SliderRenderer
    Platform Specific Control: Android.Widget.SeekBar
> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.SliderRenderer
    Platform Specific Control: System.Windows.Controls.Slider

> **Stepper**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.StepperRenderer
    Platform Specific Control: MonoTouch.UIKit.UIStepper

> Android Renderer:

    Xamarin.Forms.Platform.Android.StepperRenderer
    Platform Specific Control: Android.Widget.LinearLayout with
	four Android.Widget.Buttons

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.StepperRenderer
    Platform Specific Control: System.Windows.Controls.Border with
	four System.Windows.Controls.Buttons

> **Switch**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.SwitchRenderer
    Platform Specific Control: MonoTouch.UIKit.UISwitch

> Android Renderer:

    Xamarin.Forms.Platform.Android.SwitchRenderer
    Platform Specific Control: Android.Widget.Switch

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.SwitchRenderer
    Platform Specific Control: System.Windows.Controls.Primitives.ToggleButton

> **TimePicker**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.TimePickerRenderer
    Platform Specific Control: MonoTouch.UIKit.UIDatePicker, 
	MonoTouch.UIKit.UITextField,
	MonoTouch.UIKit.UIToolbar, MonoTouch.UIKit.UIBarButtonItems

> Android Renderer:

    Xamarin.Forms.Platform.Android.TimePickerRenderer
    Platform Specific Control: Two Android.Widget.TextViews and a Android.App.AlertDialog

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.TimePickerRenderer
    Platform Specific Control: Microsoft.Phone.Controls.DateTimePickerBase

> **WebView**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.WebViewRenderer
    Platform Specific Control: MonoTouch.UIKit.UIWebView

> Android Renderer:

    Xamarin.Forms.Platform.Android.WebRenderer
    Platform Specific Control: Android.Webkit.WebView

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.WebViewRenderer
    Platform Specific Control: Microsoft.Phone.Controls.WebBrowser

# Cell Controls #

> **EntryCell**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.EntryCellRenderer
    Platform Specific Control: MonoTouch.UIKit.UITableViewCell with a
	MonoTouch.UIKit.UITextField

> Android Renderer:

    Xamarin.Forms.Platform.Android.EntryCellRenderer
    Platform Specific Control: Android.Widget.LinearLayout contianing
	Android.Widget.TextView and Android.Widget.EditText

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.EntryCellRenderer
    Platform Specific Control: Pulls from Application.Current.Resources for
	name "EntryCell" of type System.Windows.DataTemplate

> **SwitchCell**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.SwitchCellRenderer
    Platform Specific Control: MonoTouch.UIKit.UITableViewCell with a 
	MonoTouch.UIKit.UISwitch

> Android Renderer:

    Xamarin.Forms.Platform.Android.SwitchCellRenderer
    Platform Specific Control: Android.Widget.Switch

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.SwitchCellRenderer
    Platform Specific Control: Pulls from Application.Current.Resources for name
	"SwitchCell" of type System.Windows.DataTemplate

> **TextCell**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.TextCellRenderer
    Platform Specific Control: MonoTouch.UIKit.UITableViewCel

> Android Renderer:

    Xamarin.Forms.Platform.Android.TextCellRenderer
    Platform Specific Control: Android.Widget.LinearLayout contianing two 
	Android.Widget.TextViews and Android.Widget.ImageView

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.TextCellRenderer
    Platform Specific Control: Pulls from Application.Current.Resources for
	name "TextCell", or "ListViewHeaderTextCell" or "ListViewTextCell" of type 
	System.Windows.DataTemplate depending on parent/context of the cell.

> **ImageCell**
> 
> iOS Renderer:

    Xamarin.Forms.Platform.iOS.ImageCellRenderer
    Platform Specific Control: MonoTouch.UIKit.UITableViewCell with a 
	MonoTouch.UIKit.UIImage

> Android Renderer:

    Xamarin.Forms.Platform.Android.ImageCellRenderer
    Platform Specific Control: Android.Widget.LinearLayout contianing two 
	Android.Widget.TextViews and Android.Widget.ImageView

> Windows Phone Renderer:

    Xamarin.Forms.Platform.WinPhone.ImageCellRenderer
    Platform Specific Control: Pulls from Application.Current.Resources for name 
	"ListImageCell", or "ImageCell" of type System.Windows.DataTemplate
	depending on parent/context of the cell.
