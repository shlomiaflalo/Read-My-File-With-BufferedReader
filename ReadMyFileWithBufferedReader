

import java.io.*;
import java.nio.file.Files;

      public class ReadMyFileWithBufferedReader{

        public static void main(String[]args)throws FileNotFoundException,IOException{


            InputStream readMyFileAsBytes=new FileInputStream(new File("C:\\Users\\pc2\\Desktop\\textfile.txt"));
            BufferedReader ReadFromStreamToString=new BufferedReader(new InputStreamReader(readMyFileAsBytes));
            StringBuilder Builder=new StringBuilder();
            String line;

                while((line=ReadFromStreamToString.readLine())!=null){

                    Builder.append(line+"\n");
                }

                System.out.println(Builder.toString());
                ReadFromStreamToString.close();

        }
    }
