# JavaScript-Challenges
Log of challenges attempted during JavaScript course

const mark = {
    fullName: 'Mark Miller',
    mass: 78,
    height: 1.69,

    calcBMI: function () {
        this.bmi = this.mass / (this.height ** 2);
        return this.bmi;
    }
}

const john = {
    fullName: 'John Smith',
    mass: 92,
    height: 1.95,

    calcBMI: function () {
        this.bmi = this.mass / (this.height ** 2);
        return this.bmi;
    }
}

mark.calcBMI();
john.calcBMI();

console.log(mark.bmi > john.bmi ? `Mark's BMI (${mark.bmi}) is higher than John's (${john.bmi})` : `John's BMI (${john.bmi}) is higher than Mark's (${mark.bmi})`);
