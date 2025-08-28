# prepinsta-top-100

## Gwtting Started



### 1. power of a number

<img width="1920" height="1080" alt="Screenshot from 2025-08-28 17-32-20" src="https://github.com/user-attachments/assets/fca955f2-6f49-4d4e-8a60-62a54a4bb2a4" />

<img width="900" height="270" alt="Screenshot from 2025-08-28 17-32-49" src="https://github.com/user-attachments/assets/a6a53303-7c35-4dea-9663-c43604a0fdad" />

### 2. Even or odd

<img width="1920" height="1080" alt="Screenshot from 2025-08-28 18-22-45" src="https://github.com/user-attachments/assets/ef3ab0bf-1c40-45b8-ae24-64475d04ebe2" />

<img width="900" height="308" alt="Screenshot from 2025-08-28 18-22-37" src="https://github.com/user-attachments/assets/86052642-9b55-4688-936d-78b949d26e23" />

### 3. Sum of First N Natural numbers:
### 4. Sum of N natural numbers:

<img width="1920" height="1080" alt="Screenshot from 2025-08-28 18-37-35" src="https://github.com/user-attachments/assets/20c82cd2-2d31-44ac-836d-9ea1bab0fa47" />

<img width="900" height="308" alt="Screenshot from 2025-08-28 18-37-26" src="https://github.com/user-attachments/assets/d7af65d0-899c-4944-a2b5-f8da410dd956" />

### 5.Find the Sum of the Numbers in a Given Interval

<img width="1920" height="1080" alt="Screenshot from 2025-08-28 18-58-20" src="https://github.com/user-attachments/assets/663fc944-11c8-404a-b93e-971735c99087" />

<img width="900" height="251" alt="Screenshot from 2025-08-28 18-59-31" src="https://github.com/user-attachments/assets/665c236d-31d2-4aba-a946-be147760ab51" />

```
import java.util.Scanner;
lass code{

        public static void main(String args[]){

                Scanner s = new Scanner(System.in);

                System.out.println("give Starting range");
                double n = s.nextInt();
                System.out.println("give ending range");
                double n2 = s.nextInt();


                double end=(n2*((n2+1)/2));
                double start=((n*((n+1)/2))-n);

                System.out.print(start+end);
                System.out.println("sum of first "+n+" numbers is "+(end - start));

        }

}
```
