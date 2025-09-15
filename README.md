<Window x:Class="Lab_rab1_Bikinyaev.R.V_Бпи_23_02.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        Title="MainWindow" Height="451" Width="834">
    <Grid Margin="20">
        <Grid.RowDefinitions>
            <RowDefinition Height="Auto"/>
            <RowDefinition Height="Auto"/>
            <RowDefinition Height="Auto"/>
            <RowDefinition Height="*"/>
        </Grid.RowDefinitions>
        <Grid.ColumnDefinitions>
            <ColumnDefinition Width="Auto"/>
            <ColumnDefinition Width="*"/>
        </Grid.ColumnDefinitions>

        
        <TextBlock Text="Введите дату:" Grid.Row="0" Grid.Column="0" 
                   Margin="0,0,10,10" VerticalAlignment="Center"/>
        <TextBox x:Name="InputX" Grid.Row="0" Grid.Column="1" 
                 Width="200" HorizontalAlignment="Left" Margin="0,0,0,10"/>

        
        <Button Content="Проверить високосность" Click="CheckLeapYear_Click" 
                Grid.Row="1" Grid.Column="0" Grid.ColumnSpan="2" 
                Width="200" Margin="0,0,0,10" HorizontalAlignment="Left"/>

        <Button Content="Добавить 5 дней" Click="AddDays_Click" 
                Grid.Row="2" Grid.Column="0" Grid.ColumnSpan="2" 
                Width="200" Margin="0,0,0,0" HorizontalAlignment="Left"/>
    </Grid>
</Window>
