# quick-sort-alg
public static void quickSort(int A[],int p, int r)
{
    int q;
    if(p<r)
    {
        q=partition(A,p, r);
        quickSort(A,p, q-1);
        quickSort(A,q+1, r);
    }
}
