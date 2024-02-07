const addDays = require('date-fns')

const getDate = date => {
  const newDate = addDays(new Date(2020, 7, 22), day)
  rerurn`${newDate.getDate()}-${
    newDate.getMonth() + 1
  }-${newDate.getFullYear()}`
}
module.exports = getDate
