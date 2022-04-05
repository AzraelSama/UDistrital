export class Junco {
    static CalcularProfundidad(datos: string) {
        const [diametroMts, junco] = Array.from(datos);
        const radio = parseInt(diametroMts) / 2;
        const juncoMts = parseInt(junco) / 100;
        const result = (Math.pow(radio, 2) - Math.pow(juncoMts, 2)) / (2*juncoMts);
        console.log("Profundidad Junco ===> ", result);
        if (result < 0) {
            console.log("");
            return;
        } else {
            return Math.round(result * 10.0) / 10.0;
        }
    }
}

console.log(Junco.CalcularProfundidad("3 30"));
