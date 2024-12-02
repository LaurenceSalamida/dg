hh
abstract class Animal {

    abstract void eat();

    abstract void sleep();

    abstract void makeSound();

}


class Bird extends Animal {

    @Override

    void eat() {

        System.out.println("The bird is pecking at seeds.");

    }

    @Override

    void sleep() {

        System.out.println("The bird is sleeping in its nest.");

    }

    @Override

    void makeSound() {

        System.out.println("The bird chirps.");

    }

}


class Cat extends Animal {

    @Override

    void eat() {

        System.out.println("The cat is eating fish.");

    }

    @Override

    void sleep() {

        System.out.println("The cat is sleeping on the couch.");

    }

    @Override

    void makeSound() {

        System.out.println("The cat meows.");

    }

}


class Dog extends Animal {

    @Override

    void eat() {

        System.out.println("The dog is eating kibble.");

    }

    @Override

    void sleep() {

        System.out.println("The dog is sleeping in its doghouse.");

    }

    @Override

    void makeSound() {

        System.out.println("The dog barks.");

    }

}


public class RunAina {

    public static void main(String[] args) {

        Animal bird = new Bird();

        Animal cat = new Cat();

        Animal dog = new Dog();


        System.out.println("Bird:");

        bird.eat();

        bird.sleep();

        bird.makeSound();

        System.out.println("\nCat:");

        cat.eat();

        cat.sleep();

        cat.makeSound();

        System.out.println("\nDog:");

        dog.eat();

        dog.sleep();

        dog.makeSound();

    }

}
