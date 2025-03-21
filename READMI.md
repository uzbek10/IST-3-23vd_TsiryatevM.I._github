# Практика по Github
## ИСт-3-23Вд Цирятьев М. И. Олексюк Я. А. Родин. А. М.

Из прошлой работы я узнал следующие git
команды:
*Git config
*Git init
*Git status
*Git add
*Git reset
*Git commit
*Git log
*Git diff
Две тысячи шестьсот сорок пятый год
Путин переизбран на сто третий срок
Раздавлен Китай, Америка пала
Россия теперь от Перу до Непала
Имперский штандарт на ветру гордо реет
Рухнули козни хитрых евреев
Новые церкви по миру стоят
Духовные скрепы народы хранят

Церковь свидетелей Путина
Нас солнцеликий президент
Вперёд ведёт
В его глазах сияет истина
Он уже герой легенд
Он свет несёт

Земля покорена, настало время космоса
Легион чеканит шаг тяжёлой поступью
Купола новых церквей на всех планетах
Инопланетяне у людей чистят туалеты

Церковь свидетелей Путина
Нас солнцеликий президент
Вперёд ведёт
В его глазах сияет истина
Он уже герой легенд
Он свет несёт

Церковь свидетелей Путина
Нас солнцеликий президент
Вперёд ведёт
В его глазах сияет истина
Он уже герой легенд
Он свет несёт

```
public MainWindow()
{
    InitializeComponent();
    List<string> list = new List<string>()
    {
        "Acid_Yellow",
        "carrot",
        "green"
    };
    sis.ItemsSource = list;
    MessageBox.Show("Заодно и индивидуальное задание из прошлой работы сделал");
}

private void ComboBox_SelectionChanged(object sender, SelectionChangedEventArgs e)
{
    string style = (string)sis.SelectedItem;
    Uri uri = new Uri(style + ".xaml", UriKind.Relative);
    ResourceDictionary resourceDictionary = (ResourceDictionary)Application.LoadComponent(uri);
    Application.Current.Resources.Clear();
    Application.Current.Resources.MergedDictionaries.Add(resourceDictionary);
}
```

Первая цитата 
    >цитата внутри 

1. Пункт
	1. Подпункт
		1. Подподпункт