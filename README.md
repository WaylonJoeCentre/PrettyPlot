# PrettyPlot


 var firstCategory = categories[0]; 
 var secondCategory = categories[1];
    
    entries.append("rect")
            .attr("width",10)
            .attr("height",10)
    entries.append("text")
            .text(function(category){return category[0].name})
            .classed("mycolorBlue", true)
            .attr("x",15)
            .attr("y",10)
    entries.append("text")
            .text(function(category){return category[1].name})
            .classed("mycolorRed", true)
            .attr("x",15)
            .attr("y",10)
}