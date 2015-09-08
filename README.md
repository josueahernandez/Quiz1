module.export = function double(num) {
	return num * 2;
}

module.exports = function isEven(num) {
	return !(num % 2);
};

module.exports = function fileExtension(name) {
	var period = name.lastIndexOf('.');
	if (period === -1) { return false; }
	return name.substr(period + 1);
};
