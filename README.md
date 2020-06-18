# lazycowprojects
Automatically exported from code.google.com/p/lazycowprojects
WPF C# ListView Column Width Auto & *

<ListView HorizontalAlignment="Stretch"
          Behaviours:GridViewColumnResize.Enabled="True">
        <ListViewItem></ListViewItem>
        <ListView.View>
            <GridView>
                <GridViewColumn  Header="Column *"
                                   Behaviours:GridViewColumnResize.Width="*" >
                    <GridViewColumn.CellTemplate>
                        <DataTemplate>
                            <TextBox HorizontalAlignment="Stretch" Text="Example1" />
                        </DataTemplate>
                    </GridViewColumn.CellTemplate>
                </GridViewColumn>
                <GridViewColumn  Header="Column 2*" 
                          Behaviours:GridViewColumnResize.Width="2*" >
                    <GridViewColumn.CellTemplate>
                        <DataTemplate>
                            <TextBox HorizontalAlignment="Stretch" Text="Example1" />
                        </DataTemplate>
                    </GridViewColumn.CellTemplate>
                </GridViewColumn>
                <GridViewColumn  Header="Column Auto" Width="Auto"  >
                    <GridViewColumn.CellTemplate>
                        <DataTemplate>
                            <TextBox HorizontalAlignment="Stretch" Text="Example1" />
                        </DataTemplate>
                    </GridViewColumn.CellTemplate>
                </GridViewColumn>
                <GridViewColumn  Header="50 S"
                                   Behaviours:GridViewColumnResize.Width="50" >
                    <GridViewColumn.CellTemplate>
                        <DataTemplate>
                            <TextBox HorizontalAlignment="Stretch" Text="E" />
                        </DataTemplate>
                    </GridViewColumn.CellTemplate>
                </GridViewColumn>
                <GridViewColumn  Header="50" Width="50" >
                    <GridViewColumn.CellTemplate>
                        <DataTemplate>
                            <TextBox HorizontalAlignment="Stretch" Text="E" />
                        </DataTemplate>
                    </GridViewColumn.CellTemplate>
                </GridViewColumn>
        </GridView>
        </ListView.View>
</ListView>
