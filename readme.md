#Sample project of JSON parsing

Sample project which parse JSON data from Web site. This project make table with JSON data.

![Screen Shot](http://farm9.staticflickr.com/8434/7682724936_f2cc9e63f7_o.png)

You can see how useful JSON is in iOS. For example, the code below take datas from JSON. This is wonderful !

    cell.textLabel.text = 
    [[_JSON valueForKeyPath:@"rss.channel.item.title"] objectAtIndex:indexPath.row];
    cell.detailTextLabel.text =
    [[_JSON valueForKeyPath:@"rss.channel.item.description"] objectAtIndex:indexPath.row];
