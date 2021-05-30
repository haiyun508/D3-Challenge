function renderXCircles(circlesGroup, newXScale, chosenXAxis) {
  circlesGroup.transition()
    .duration(1000)
    .attr("cx", d => newXScale(d[chosenXAxis]))
  return circlesGroup;
}
function renderYCircles(circlesGroup, newYScale, chosenYAxis) {
  circlesGroup.transition()
    .duration(1000)
    .attr("cy", d => newYScale(d[chosenYAxis]))
  return circlesGroup;
}
s

  circlesGroup = renderXCircles(circlesGroup, xLinearScale, chosenXAxis);
  circlesGroup = renderYCircles(circlesGroup, xLinearScale, chosenYAxis);
