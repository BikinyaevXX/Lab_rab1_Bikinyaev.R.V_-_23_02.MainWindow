<Window x:Class="Lab_rab1_Bikinyaev.R.V_Бпи_23_02.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:Lab_rab1_Bikinyaev.R.V_Бпи_23_02"
        mc:Ignorable="d"
        Title="MainWindow" Height="450" Width="800">
    <Grid>
        <Grid Margin="0,0,0,7">
            <StackPanel Margin="0,0,0,10">
                <TextBlock Text="Введите дату:" Margin="0,0,0,10"/>

                <TextBox x:Name="InputX" Width="200" Margin="0,0,0,10"/>

                <TextBlock Text="Выберите функцию:" Margin="0,10,0,10"/>
                <ComboBox x:Name="FunctionSelector" Width="200" Margin="0,0,0,10">
                    <ComboBoxItem Content="Високосность"/>
                    <ComboBoxItem Content="+ 5 дней"/>
                </ComboBox>
                <Button Content="Рассчитать" Width="100"  Margin="0,10,0,10"/>
            </StackPanel>
        </Grid>

    </Grid>
</Window>
